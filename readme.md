
# [Dependency: BepInEx](https://img.shields.io/github/downloads/bepinex/bepinex/total.svg)

<p align="center">
    <img src="https://avatars2.githubusercontent.com/u/39589027?s=256">
</p>

## BepInEx **[Source](https://github.com/BepInEx/BepInEx)**
![Github All Releases](https://img.shields.io/github/downloads/bepinex/bepinex/total.svg)
![GitHub release](https://img.shields.io/github/release/bepinex/bepinex.svg)

## BepInEx Framework + API
This is the pack of all the things you need to both start using mods, and start making mods using the BepInEx framework.

To install, just extract the .zip so that the winhttp.dll file is sitting next to your Risk of Rain 2.exe file. That's the only installation step.
I'm aware of some issues related to logging, so I'll release a second version sometime later (and maybe with more included plugins).

## What each folder is for:
BepInEx/plugins - This is where normal mods/plugins are placed to be loaded.
For developers: There's no set format for what you need to name your plugins to load; if they're a valid plugin .dll file, they'll be loaded.
However please be considerate and isolate your files in their own folders, to prevent clutter, confusion, and in general, dependency hell. For example: BepInEx/plugins/YourMod/Plugin.dll

BepInEx/patchers - These are more advanced types of plugins that need to access Mono.Cecil to edit .dll files during runtime. Only copy paste your plugins here if the author tells you to.
For developers: More info here: [Github All Releases](https://github.com/BepInEx/BepInEx/wiki)

BepInEx/monomod - MonoMod patches get placed in here. Only copy paste your plugins here if the author tells you to.

BepInEx/config - If your plugin has support for configuration, you can find the config file here to edit it.

BepInEx/core - Core BepInEx .dll files, you'll usually never want to touch these files (unless you're updating)


Bepis Injector Extensible

---

Unity plugin framework

**[Latest releases](https://github.com/BepInEx/BepInEx/releases)**

**[Bleeding Edge builds](http://builds.bepis.io/bepinex_be)**

**[How to install](https://github.com/bbepis/BepInEx/wiki/How-to-install)**

**[User and developer guides](https://github.com/BepInEx/BepInEx/wiki)**

## Used libraries
- [NeighTools/UnityDoorstop](https://github.com/NeighTools/UnityDoorstop) - 2.7.1.0 ([df7d636](https://github.com/NeighTools/UnityDoorstop/commit/df7d6366d8dc69f024c61cd31e6f690eb44ce57a))
- [pardeike/Harmony](https://github.com/pardeike/Harmony) - pre-2.0 ([443f551](https://github.com/pardeike/Harmony/commit/443f551ec45ecf409755b5979a4466343197de03))
- [0x0ade/MonoMod](https://github.com/0x0ade/MonoMod) - v19.05.01.01 ([934a8ae](https://github.com/0x0ade/MonoMod/commit/934a8ae921affac0093757d23c6f3ead34e996ac))
- [jbevain/cecil](https://github.com/jbevain/cecil) - 0.10.3 ([fb289a7](https://github.com/jbevain/cecil/commit/fb289a7cd80ceb6af5c86e7c7ecce9bf1e98b8fe))

## Credits
- [Usagirei](https://github.com/Usagirei) - Code for using the console and for assisting with technical support
- [essu](https://github.com/exdownloader) - Project logo, moral support and lots of misc. help
- [denikson](https://github.com/denikson) - [UnityDoorstop](https://github.com/NeighTools/UnityDoorstop) for the patchless loader
- [nn@](https://twitter.com/NnAone2cmg) - Japanese translation of the wiki