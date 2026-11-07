# Awesome Gravity Defied [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Gravity Defied ports, remakes, level tools, and experiments on GitHub.

Gravity Defied is a motorcycle trial racing game originally developed by Codebrew Software for J2ME in 2004. This list explores the community projects that keep it running on new platforms and make it possible to create new tracks.

## Mobile Apps

- [evgenyzinoviev/gravitydefied](https://github.com/evgenyzinoviev/gravitydefied) - Classic unofficial Android port, with an in-game manager for community level packs. Java.
- [alekseypokhilko/GDTR_Alive](https://github.com/alekseypokhilko/GDTR_Alive) - Extended version of the Android port with training, recorded runs, ghosts, themes, gamepad support, and a beta track editor. Java.
- [cosmicog/gravitydefied](https://github.com/cosmicog/gravitydefied) - Fork of the classic Android port with a dark theme, Gradle builds, and a replacement set of harder tracks. Java.
- [figonzal1/gravitydefied](https://github.com/figonzal1/gravitydefied) - Fork of the classic Android port updated for modern Android. Java.
- [PlayFDroid/gravity-defied](https://github.com/PlayFDroid/gravity-defied) - Android modernization based on the classic port and figonzal1's maintenance, with F-Droid distribution support. Java.

## Desktop

- [rgimad/gravity_defied_cpp](https://github.com/rgimad/gravity_defied_cpp) - C++ and SDL2 port of the classic game, also used as the foundation for several community ports. C++.
- [Halvanhelv/gravity-defied](https://github.com/Halvanhelv/gravity-defied) - Experimental DragonRuby GTK port based on the C++ and TypeScript ports, with recorded autopilot runs and a browser build. Ruby.
- [kvckr/slop-defied](https://github.com/kvckr/slop-defied) - .NET and raylib-cs port derived from decompiled J2ME classes, with a documented mapping from the original classes to C#. C#.

## Web

- [yurkagon/gravity-defied-web](https://github.com/yurkagon/gravity-defied-web) - Browser port based on the C++ version, using Canvas rendering, keyboard and touch controls, and local progress saves. TypeScript. [Play](https://yurkagon.github.io/gravity-defied-web/).
- [LitoMore/gravity-defied-web](https://github.com/LitoMore/gravity-defied-web) - WebAssembly adaptation of the C++ and SDL2 port, with keyboard, touch, and gamepad controls and IndexedDB saves. C++.
- [MihailPreis/Wheelie](https://github.com/MihailPreis/Wheelie) - Browser port based on the Android version, with community level packs, a track editor, shareable replays, and ghost racing. TypeScript. [Play](https://mihailpreis.github.io/Wheelie/).

## Handhelds and Embedded Devices

- [antoxa2584x/regravity_defied](https://github.com/antoxa2584x/regravity_defied) - Reimplementation with a shared game core and native builds for Game Boy Advance, Nintendo DS/DSi, Nintendo 3DS/2DS, and PSP. C.
- [antim0118/gravity_defied_psp](https://github.com/antim0118/gravity_defied_psp) - PSP port based on the C++ version, using gLib2D and intraFont-G. C++.
- [LokiDSx/Gravity-Defied-Vita](https://github.com/LokiDSx/Gravity-Defied-Vita) - PS Vita adaptation of the C++ and SDL2 port, with custom track packs, zoom, and a dark theme. C++.
- [Qwe2me/gravity_defied_cpp](https://github.com/Qwe2me/gravity_defied_cpp) - Adaptation of the C++ port for Miyoo CFW, with a dedicated cross-compilation Makefile. C++.
- [XimikBoda/GravityDefiedCppVxp](https://github.com/XimikBoda/GravityDefiedCppVxp) - Adaptation of the C++ port for the MediaTek MRE platform and VXP applications. C++.
- [mulfyx/wiphone-lab](https://github.com/mulfyx/wiphone-lab) - WiPhone firmware project containing an optional ESP32 port derived from the C++ version in `src/gravity_defied/`. C/C++.
- [BolgarMaxym97/gravity-defied-arduboy-port](https://github.com/BolgarMaxym97/gravity-defied-arduboy-port) - Unofficial Arduboy implementation with monochrome graphics, fixed-point physics, and ten tracks; its README documents current build limitations. C++.

## Level Editors and Tools

- [Igorgro/GD-editor](https://github.com/Igorgro/GD-editor) - Browser-based level editor for the Android game, with a grid, themes, and drag-and-drop controls. JavaScript.
- [PikMike/CFGD](https://github.com/PikMike/CFGD) - Generates Gravity Defied tracks from Codeforces rating graphs, with installation instructions for Android level packs. Python.
- [mrtnvgr/mrg](https://github.com/mrtnvgr/mrg) - Library for parsing and serializing Gravity Defied level files. Rust.
- [LooMaclin/gravity_defied_rs](https://github.com/LooMaclin/gravity_defied_rs) - Experimental `levels.mrg` parser and track viewer using ggez, with a physics playground. Rust.
- [teh-lolcat/mrg-collector](https://github.com/teh-lolcat/mrg-collector) - Utility that combines multiple `.mrg` level files into one. C#.

## Packaging and Distribution

- [PortMaster: Gravity Defied](https://github.com/PortsMaster/PortMaster-New/tree/main/ports/gravitydefied) - PortMaster package for Linux handhelds, including a launcher, controls, and custom-level instructions, based on the C++ port.
- [ohol-vitaliy/PortMaster-GravityDefied](https://github.com/ohol-vitaliy/PortMaster-GravityDefied) - Docker-based build instructions for the PortMaster version.
- [Luvrok/gravity-defied-cpp-flake](https://github.com/Luvrok/gravity-defied-cpp-flake) - Nix flake for building and running the C++ port; the README notes that progress is not saved between sessions. Nix.

## Clones and Experiments

Independent interpretations and small experiments inspired by Gravity Defied. Their physics and tracks may differ from the classic game.

- [re-mouse/GravitiyDefiedClone](https://github.com/re-mouse/GravitiyDefiedClone) - Unity clone with procedural terrain built using Sprite Shape. C#.
- [Antot-12/Gravity-Defied](https://github.com/Antot-12/Gravity-Defied) - Pygame interpretation with neon visuals, procedural tracks, multiple bikes, and difficulty modes. Python.
- [Firemoon777/gravity-defied](https://github.com/Firemoon777/gravity-defied) - Terminal clone written in GNU sed, with one challenging level and a shell launcher. GNU sed/Shell.
- [IlyaSolomatin/gravity_defied_terminal](https://github.com/IlyaSolomatin/gravity_defied_terminal) - Terminal implementation using curses and Unicode Braille graphics. Python.

## Contributing

Suggestions and corrections are welcome! Read the [contribution guidelines](CONTRIBUTING.md) before opening a pull request.

Entries were checked against repository READMEs or source files on November 7, 2026. This is a curated selection: unchanged forks, unrelated projects, and repositories without enough information to describe their purpose are omitted. A listing does not imply that its builds or gameplay have been tested.

## License

This list is released under [CC0 1.0 Universal](LICENSE). Listed projects retain their own licenses. This community list is not affiliated with Codebrew Software; the original game's name and assets belong to their respective owners.
