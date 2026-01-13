// Configuração do Jogo
const config = {
    type: Phaser.AUTO,
    width: 800,
    height: 400,
    physics: {
        default: 'arcade',
        arcade: {
            gravity: { y: 1000 }, // Gravidade forte como no Sonic
            debug: false
        }
    },
    scene: {
        preload: preload,
        create: create,
        update: update
    }
};

const game = new Phaser.Game(config);
let player;
let cursors;

function preload() {
    // Carregue seus assets abertos aqui
    this.load.image('sky', 'https://labs.phaser.io/assets/skies/space3.png');
    this.load.spritesheet('sonic', 'https://labs.phaser.io/assets/sprites/phaser-dude.png', { frameWidth: 32, frameHeight: 48 });
}

function create() {
    this.add.image(400, 300, 'sky');

    // Criando o jogador com física
    player = this.physics.add.sprite(100, 300, 'sonic');
    player.setBounce(0.1); // Quica um pouco ao cair
    player.setCollideWorldBounds(true); // Não sai da tela

    // Configuração de fricção e aceleração manual
    player.setMaxVelocity(600, 1000); 
    player.setDragX(500); // Isso faz ele deslizar até parar

    cursors = this.input.keyboard.createCursorKeys();
    
    // Para Celular: Detecta toque na tela
    this.input.on('pointerdown', () => {
        if (player.body.touching.down) {
            player.setVelocityY(-500);
        }
    });
}

function update() {
    // Aceleração Progressiva (Momentum)
    if (cursors.left.isDown) {
        player.setAccelerationX(-800);
    } else if (cursors.right.isDown) {
        player.setAccelerationX(800);
    } else {
        player.setAccelerationX(0);
    }

    // Pulo no teclado
    if (cursors.up.isDown && player.body.touching.down) {
        player.setVelocityY(-500);
    }
}
