---
title: "FPS Patches & Mods"
mathjax: true
layout: post
categories:
  - info

# Menu

navigation:                # accepts {file, title, url, icon, sidebaricon}
  - {file: "home.md", title: "Home"}
  - {file: "about-general-knowledge.md", title: "About & General Knowledge"}
  - {file: "Jailbreak.md", title: "Jailbreak"}
  - {file: "gaming.md", title: "Games, Updates & DLC"}
  - {file: "hacks-homebrew.md", title: "Hacks & Homebrew"}
---

## What mods can I install and how do 60FPS patches work?

* While PS4 mods are not as popular as some other platforms like PSVita, PS3, there are some mods you can do to your games than can range from character model swaps, music swaps, etc.
* FPS patches work by modifying some lines from the game's main executable (eboot.bin) that will toggle FPS unlock by sacrificing resolution. Basically higher FPS will need lower resolution.
* Here is a list of all 60FPS patches available:
<a href="https://illusion0001.github.io/patch/"> PS4 60FPS & Resolution Patch List </a>

## Enough talk, let's start...

### 60FPS & Resolution Patches

* Start by loading [GoldHEN 2.3](/orbisunjailed/fresh-start-jailbreak) or newer on your PS4.
* Download the app GoldHEN Cheats Manager from the [Release Page](https://github.com/GoldHEN/GoldHEN_Cheat_Manager/releases/latest).
* Copy it to the root of your USB drive and install it from the PS4 Package Installer.
* Once the application is installed, download the plugins from the GoldHEN Plugins Repository [Releases Page](https://github.com/GoldHEN/GoldHEN_Plugins_Repository/releases/latest).
* Using a FTP client, copy the plugin files to `/data/GoldHEN/plugins`.
* Make a text file called `plugins.ini` if it does not exist, add the following to the file, if the line `[default]` already exist, just add `/data/GoldHEN/plugins/game_patch.prx` to the line below it.
```
[default]
/data/GoldHEN/plugins/game_patch.prx
```
* Update the database using the GoldHEN Cheats Manager app and you can now start using Custom Game Patches without needing a computer after the setup!

### Other mods

 * These mods are the scarce ones, that are already built as pkg to install. As a result I will only provide links to some mods I found:
    * <a href="https://www.psx-place.com/forums/ps4-game-mods.226/"> PS4 Game Mods Subforum </a>
    * <a href="https://www.psxhax.com/threads/mortal-kombat-xl-modpack-2-for-ps4-4-user-friendly-players.5121/"> Mortal Kombat XL Modpack </a>
    * <a href="https://old.reddit.com/r/ps4homebrew/comments/qx78u8/resident_evil_2_classic_modpack/"> Resident Evil 2 Classic Modpack </a>
    * <a href="https://old.reddit.com/r/ps4homebrew/comments/quxe28/resident_evil_3_classic_modpack/"> Resident Evil 3 Classic Modpack </a>
