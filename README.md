<div align="center">
	<div>
    <a href="https://flame-engine.org/">
		<img width="300" src="media/logo.png" alt="Awesome Flame">
    </a>
	</div>
  <p style="margin-top:30px;" align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="Awesome" src="https://awesome.re/badge-flat.svg" />
    </a>
    <a href="http://creativecommons.org/publicdomain/zero/1.0">
      <img alt="License: CC0" src="https://img.shields.io/badge/license-CC0-lightgray?style=flat-square" />
    </a>
    <a href="https://flame-engine.org">
      <img alt="Powered by Flame" src="https://img.shields.io/badge/Powered%20by-%F0%9F%94%A5-orange.svg?style=flat-square" />
    </a>
    <a href="https://github.com/flame-engine/awesome-flame/blob/main/CONTRIBUTING.md">
      <img alt="Add your project" src="https://img.shields.io/badge/-Add%20your%20project-blue?style=flat-square" />
    </a>
  </p>
</div>

# Awesome Flame

> A curated list of games, libraries, and articles related to the Flame Engine for Flutter.

[Flame](https://flame-engine.org/) is a minimalist 2D game engine for Flutter that provides a nice set of somewhat independent modules you can choose from to build your games.

## Contents

- [Articles & Tutorials](#articles--tutorials)
- [Plugins & Libraries](#plugins--libraries)
  - [Official](#official)
  - [Community](#community)
- [Projects](#projects)
  - [Open Source](#open-source)
  - [App Releases](#app-releases)
- [Non-English Content](#non-english-content)

## Articles & Tutorials

### Beginner Tutorial Series by [Alekhin](https://github.com/japalekhin)

- [Create a Mobile Game with Flutter and Flame - Beginner Tutorial (Introduction)](https://jap.alekhin.io/create-mobile-game-flutter-flame-beginner-tutorial)
- [2D Casual Mobile Game Tutorial - Step by Step with Flame and Flutter (Part 1 of 5)](https://jap.alekhin.io/2d-casual-mobile-game-tutorial-flame-flutter-part-1)
- [Game Graphics and Animation Tutorial - Step by Step with Flame and Flutter (Part 2 of 5)](https://jap.alekhin.io/game-graphics-and-animation-tutorial-flame-flutter-part-2)
- [Views and Dialog Boxes Tutorial - Step by Step with Flame and Flutter (Part 3 of 5)](https://jap.alekhin.io/views-dialog-boxes-tutorial-flame-flutter-part-3)
- [Scoring, Storage, and Sound Tutorial - Step by Step with Flame and Flutter (Part 4 of 5)](https://jap.alekhin.io/scoring-storage-sound-tutorial-flame-flutter-part-4)
- [Game Finishing and Packaging Tutorial - Step by Step with Flame and Flutter (Part 5 of 5)](https://jap.alekhin.io/game-finishing-packaging-tutorial-flame-flutter-part-5)

<!--lint ignore double-link-->
### Articles by [Fireslime](https://fireslime.xyz/)

<!--lint ignore double-link-->
- [Creating a virtual controller with Stack on Flame](https://fireslime.xyz/articles/20190902_Flame_Virtual_Controller_With_Stack.html)
- [Basic Camera usage on Flame](https://fireslime.xyz/articles/20190911_Basic_Camera_Usage_In_Flame.html)

### Articles by [wolfenra.in](https://wolfenra.in)

- [Dart Box2D Fundamentals series](https://blog.wolfenra.in/series/dart-box2d-fundamentals/)

### Articles by [Yayocode][2]

- [1. Getting started: Setting up the project](https://yayocode.blogspot.com/2022/08/flame-getting-started-setting-up-project_4.html)
- [2. The world, bodies, shapes, and fixtures](https://yayocode.blogspot.com/2022/08/flame-world-bodies-shapes-and-fixtures.html)
- [3. Body types: dynamic, static & kinematic](https://yayocode.blogspot.com/2022/08/flame-body-types-dynamic-static.html)
- [4. Friction, density & restitution](https://yayocode.blogspot.com/2022/08/flame-friction-density-restitution.html)
- [5. Forces, impulses & linear velocity](https://yayocode.blogspot.com/2022/08/flame-forces-impulses-linear-velocity.html)
- [6. Bodies and sprites](https://yayocode.blogspot.com/2022/08/flame-bodies-and-sprites.html)
- [7. Collisions](https://yayocode.blogspot.com/2022/08/flame-collisions.html)
- [8. Collisions with animated sprites](https://yayocode.blogspot.com/2022/08/flame-collisions-with-animated-sprites.html)

### Tutorials by [raywenderlich.com](https://www.raywenderlich.com/)

<!--lint ignore double-link-->
- [Building Games in Flutter with Flame: Getting Started](https://www.raywenderlich.com/27407121-building-games-in-flutter-with-flame-getting-started) - By [Vincenzo Guzzi](https://twitter.com/vguzzi_dev)

### Other Articles & Tutorials

- [Killing gnats with Flutter and Flame](https://medium.com/flutter-community/killing-gnats-with-flutter-and-flame-77fa9224ccaa) - Build your first game with ads and i18n. By [Bo Hellgren](https://medium.com/@bo.hellgren)

- [Flutter Web and Flame](https://github.com/AseemWangoo/experiments_with_web) - Hands on with Flame for web. By [Aseem Wangoo](https://flatteredwithflutter.com/how-to-create-game-in-flutter-web-using-flame/)

- [Simple Platformer - Flame Game Development Series](https://youtube.com/playlist?list=PLiZZKL9HLmWPyd808sda2ydG-dhexNONV) - 2D platformer without using Forge2d. By [DevKage][1].

- [Dino Run - Flutter Game Development Series with Flame](https://youtube.com/playlist?list=PLiZZKL9HLmWOmQgYxWHuOHOWsUUlhCCOY) - An easy to follow tutorial on how to make 2D mobile game in Flutter using Flame engine. By [DevKage][1].

- [Spacescape - Flutter Game Development Series with Flame](https://www.youtube.com/playlist?list=PLiZZKL9HLmWPL0URlq9WLng1A_g1LDuxx) - An easy to follow tutorial on how to make 2D mobile game in Flutter using Flame engine. By [DevKage][1].

### Examples

- [Maze generator](https://github.com/Dannark/FlameExamples) - List of algorithm examples to solve problems like Maze generation and more. By [Dannark](https://github.com/Dannark/)

## Plugins & Libraries

### Official

<!--lint ignore double-link-->
- [flame_gamepad](https://github.com/flame-engine/flame_gamepad) - Flutter Gamepad Support.
- [flame_geom](https://github.com/flame-engine/flame_geom) - Complement Flame with APIs for handling shapes and geometric operations.
- [flame_scrolling_sprite](https://github.com/flame-engine/flame_scrolling_sprite) - Easy to use sprites that repeats itself on an area.
- [play_games](https://github.com/flame-engine/play_games) - A simple wrapper on top of Google Play Games Services (GPGS), including auth, achievement, and more.

### Community

- [bonfire](https://github.com/RafaelBarbosatec/bonfire) - RPG maker. By [rafaelbarbosatec](https://github.com/RafaelBarbosatec)
- [flame_texturepacker](https://github.com/Brixto/flame_texturepacker) - Import spritesheets from TexturePacker. By [Brixto](https://github.com/Brixto)

## Projects

### Open Source

#### Casual

<!--lint ignore double-link-->
- [Bob Box](https://github.com/fireslime/bounce_box) - A simple casual game that you can play with one finger. Tap to stop, avoid obstacles! By [FireSlime](https://fireslime.xyz)
- [Snaake!](https://github.com/lucasnlm/snaake-flutter) - A simple casual snake game. By [lucasnlm](https://github.com/lucasnlm)
- [Ghost Rigger](https://github.com/Float-like-a-dash-Sting-like-a-dart/GhostRigger) - A cyberpunk inspired puzzle game, build for Flutter Hackathon Hack20. By [b099l3](https://github.com/b099l3) and [ernestoyaquello](https://github.com/ernestoyaquello)
- [Ant Squash](https://github.com/sourabhgupta811/Ant-Squash) - A simple casual bug squashing game that you can play with one finger. Tap to kill, stop ants from eating the sweet! By [Sourabh Gupta](https://www.linkedin.com/in/sourabhgupta811/)
- [Color Mixer](https://github.com/androideen/color_mixer_flame) - A color mixer game built with Flame 1.0.0-rc8. Tap 2 colors to mix them and help player pass obstacles.
- [Flappy Flame](https://github.com/Pierre-Monier/flappy_flame) - A flappy bird clone made with Flame 1.0.0-rc5. By [Pierre-Monier](https://github.com/Pierre-Monier)
- [Spacescape](https://github.com/ufrshubham/spacescape) - A 2D top-down space shooter made using Flutter and Flame engine. Get it on [Play Store](https://play.google.com/store/apps/details?id=com.nobs.spacescape). By [DevKage][1].
- [New Super Jumper](https://github.com/Yayo-Arellano/flutter_games_compilation/tree/main/new_super_jumper) - A doodle jump clone made with Flame and Forge2D. By [Yayocode][2].

#### Endless Runner

<!--lint ignore double-link-->
- [BGUG](https://github.com/fireslime/bgug) - Break Guns Using Gems is a fast paced side-scrolling platformer with innovative controls and and a gun-related twist. By [FireSlime](https://fireslime.xyz)

- [Dino Run](https://github.com/ufrshubham/dino_run) - A 2D infinite side scroller mobile game made in Flutter using Flame engine. Get it on [Play Store](https://play.google.com/store/apps/details?id=com.nobs.dino_run). By [DevKage][1].

#### Platformer

- [Flutters](https://github.com/ecklf/flutters) - A mixture of Flappy Bird and Doodle Jump. By [ecklf](https://github.com/ecklf)

- [Simple Platformer](https://github.com/ufrshubham/flame_simple_platformer) - A 2D platformer made using Flame engine. By [DevKage][1].

#### RPG

- [Darkness Dungeon](https://github.com/RafaelBarbosatec/darkness_dungeon) - Simple RPG. By [rafaelbarbosatec](http://rafaelbarbosatec.github.io/)

### App Releases

#### Arcade

<!--lint ignore double-link-->
- Air Hockey Classic - [Android](https://play.google.com/store/apps/details?id=com.ignacemaes.airhockey), [iOS](https://apps.apple.com/us/app/air-hockey-classic/id1535374629) - Play the classic 'Air Hockey' arcade game now on your mobile device! By [Ignace Maes](https://ignacemaes.com/)

#### Board

<!--lint ignore double-link-->
- Four In A Row - [Android](https://play.google.com/store/apps/details?id=com.ignacemaes.fourinarow), [iOS](https://apps.apple.com/us/app/four-in-a-row-classic/id1495540053) - Play the classic 'Four In A Row' board game! Will you be the first to connect 4 of your chips? Challenge the AI, or play against your friends and family. By [Ignace Maes](https://ignacemaes.com/)

<!--lint ignore double-link-->
- Omnichess - [Web](https://www.omnichess.club), [Android](https://play.google.com/store/apps/details?id=club.omnichess), [iOS](https://apps.apple.com/us/app/omnichess/id1593756511) - Create and play your own Chess variants! 2-8 players. Online/AI. Square/Hexagonal tiled boards. By [Chirag Patel](https://github.com/orgs/Omnimind-Ltd)

#### Casual

<!--lint ignore double-link-->
- KINGA - [Android](https://play.google.com/store/apps/details?id=com.knoeyes.games.kinga), [iOS](https://apps.apple.com/us/app/kinga/id1506422810) - Protect the cookie from the pesky flies. By [Kevin Omyonga](https://kevinomyonga.com)

<!--lint ignore double-link-->
- Dhoruba - [Android](https://play.google.com/store/apps/details?id=com.knoeyes.games.dhoruba), [iOS](https://apps.apple.com/ke/app/dhoruba/id1542324108) - Can You Stand The Rain? By [Kevin Omyonga](https://kevinomyonga.com)

<!--lint ignore double-link-->
- Toilet Racer - [Android](https://play.google.com/store/apps/details?id=dr.achim.toilet_racer) - Turn your bathroom into a magical sanctuary and become the toilet ninja! By [Philipp Mudra](https://github.com/PMudra), [Tim Wiechmann](https://github.com/drachim-dev)

<!--lint ignore double-link-->
- Wormo - [Android](https://play.google.com/store/apps/details?id=com.tbuonomo.wormo), [iOS](https://apps.apple.com/us/app/wormo-the-game/id1530797595) - Meet Wormo the gooey worm in this wonderful casual game! Think you can put wormo in the nest? Think again, it requires an extraordinary technique. 
By Tommy Buonomo ([Frenchie Games](https://frenchiegames.app/#/))

<!--lint ignore double-link-->
- Hyper Hexagon - [Web version](https://thecocce.itch.io/hyper-hexagon) - Hexagonal board game challenge - A classical and futuristic. Inspired by the old classic Hexxagon '90s game. By [TheCocce](https://github.com/thecocce/)

#### Metroidvania

<!--lint ignore double-link-->
- [Tales of a Lost Mine](https://fireslime.xyz/games/tales.html) - [Android](https://play.google.com/store/apps/details?id=xyz.fireslime.tales&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1) - An awesome platform-adventure Metroidvania. Get in the role of a brave explorer and uncover the secrets of a long lost time. By [FireSlime](https://fireslime.xyz)

#### Music

<!--lint ignore double-link-->
- Relo Music Instrument - [Android](https://play.google.com/store/apps/details?id=ch.astrate.relo), [iOS](https://apps.apple.com/us/app/relo-music-instrument/id1547638708) - First ever RELATIVE music instrument, which is especially suitable for mobile devices and improvisation. 

#### Online Multiplayer

<!--lint ignore double-link-->
- Penguin Chat - [Android](https://play.google.com/store/apps/details?id=com.sanjeev.penguin_chat_game), [GitHub](https://github.com/Shadow60539/club_penguin_game) - Players use cartoon penguin avatars and chat in a virtual world without losing their real-time position. By [Sanjeev Madhav](https://sanjeevmadhav.com)

#### Puzzle Games

<!--lint ignore double-link-->
- Ripple Effect Puzzle - [Android](https://play.google.com/store/apps/details?id=com.tbuonomo.rippleeffectpuzzle), [iOS](https://apps.apple.com/us/app/id1521454937) - A sophisticated variation of Sudoku.
By Tommy Buonomo ([Frenchie Games](https://frenchiegames.app/#/))

- Tile Paths - [Android](https://play.google.com/store/apps/details?id=com.naslausky.tile_paths) - Drag the tiles and find the best path to make your character collect all items while avoiding the enemy. With 10 different stages you can challenge your friends to see who gets the best highscore in every one of them. By [Naslausky](https://github.com/naslausky)

#### Sports

<!--lint ignore double-link-->
- Pool Ball Classic - [Android](https://play.google.com/store/apps/details?id=com.ignacemaes.poolball), [iOS](https://apps.apple.com/us/app/pool-ball-classic/id1557034712) - Play 8 Ball Pool like you know and love on your mobile device featuring 3D graphics, realistic physics, and a challenging AI mode. By [Ignace Maes](https://ignacemaes.com/)

- Cycling Escape - [Android](https://play.google.com/store/apps/details?id=be.wive.cyclingescape), [iOS](https://apps.apple.com/us/app/cycling-escape/id1553634302#?platform=iphone), [GitHub](https://github.com/ikbendewilliam/CyclingEscape) - You start off with only one rider. Compete in races to start earning money. Unlock more team mates and compete in more extreme and longer races. Keep going and win the ultimate world tour! By [ikbendewilliam](https://github.com/ikbendewilliam)

#### Tower Defense

- Xtrike - [Android](https://play.google.com/store/apps/details?id=online.xtrike.xtrike) - An awesome strategic tower defense game. Build your battle units and destroy enemies. By [White Wood City](http://www.xtrike.online/)

## Non-English Content

- [Mandarin Chinese (中文)](https://github.com/flame-engine/awesome-flame/blob/main/CONTENT_ZH.md)

## Contributing

[Please read the contribution guidelines](https://github.com/flame-engine/awesome-flame/blob/main/CONTRIBUTING.md)

<!-- Add ref links here -->
[1]: <https://www.youtube.com/devkage> 'DevKage'
[2]: <https://www.yayocode.com> 'Yayocode'
