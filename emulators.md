---
title: "Emulators"
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

## What are emulators and what systems can I play on PS4?

* Emulators are applications that act/behave like a completely different system in order to play games released before / not natively made for PS4.
* On the PS4, there are 2 types of emulators: official (either made by Sony or the company that made/owns the rights to the emulated console) and ports (fan-made emulators).
* Officially the PS4 can emulate PS1, PS2, PSP & Sega Saturn.
* Ports allow the PS4 to emulate MSDOS, NES, every GameBoy, MAME, Atari Lynx, Neo-Geo Pocket, SNES, VirtualBoy, WonderSwan, Nintendo 64, PS1, Sega Genesis/MegaDrive, Nintendo DS, FB Alpha Arcades, Capcom PS1,2 &3, MSX, NEC PC-FX, NEC PC Engine, Sega Saturn, Sega Dreamcast, old PC games, Atari 2600, Atari Jaguar, Vectrex, PSP, various ports, 3DO.

## Enough talk, let's start...

### Official Emulators (PS1, PS2, PSP & Sega Saturn)

#### PS1

* Before attempting, check compatibility list here (if a game is not on the list, feel free to test it):
<a href="https://www.psdevwiki.com/ps4/PS1_Classics_Emulator_Compatibility_List"> PS1 Compatibility List </a>
* Download and extract PSX-FPKG:
   * <a href="https://www.psx-place.com/threads/psx-fpkg-0-2-by-jabu-new-tool-to-convert-ps1-games-for-ps4.30498/"> PSX-FPKG </a>
   * [Backup mirror](/backupfiles/PSX-FPKG_v02.7z)
* Download your favourite PS1 rom. Make sure it is in a .bin and .cue file format.
* Launch PSX-FPKG. In the Disc section select the .bin file.
* Rename the tile if it hasn't updated to the game name. Add your own NP Title if it hasn't updated.
* You can select a custom Icon & Background image to make it prettier on the homescreen and when you launch it.
   * Icon resolution must be 512x512
   * Background resolution must be 1920x1080
* Select Create fPKG and wait until it's finished. For multi-disc games you must make new pkg but keeping the same NP Title. When you're done playing a game that requires one disc, save then install and override it with the new pkg.
* Add the created pkg to the root of a USB drive and install it on your PS4 by navigating to Settings > GoldHEN > Package Installer.
* Done.

#### PS2

* Before attempting, check compatibility list here (if a game is not on the list, feel free to test it):
<a href="https://www.psdevwiki.com/ps4/PS2_Classics_Emulator_Compatibility_List"> PS2 Compatibility List </a>
* Download and extract PS2-FPKG:
   * <a href="https://www.psx-place.com/threads/release-ps2-fpkg-0-6-by-jabu-new-tool-to-convert-ps2-games-for-ps4.30350/"> PS2-FPKG </a>
* Download your favourite PS2 rom. Make sure it is either in a .ISO or .bin and .cue file format.
* Launch PS2-FPKG. In the Disc section select the .ISO or .bin file. Also select the other disc .ISO or .bin files in the appropriate section.
* Rename the tile if it hasn't updated to the game name. Add your own NP Title if it hasn't updated.
* You can select a custom Icon & Background image to make it prettier on the homescreen and when you launch it.
   * Icon resolution must be 512x512
   * Background resolution must be 1920x1080
* Select Create fPKG and wait until it's finished.
* Add the created pkg to the root of a USB drive and install it on your PS4 by navigating to Settings > GoldHEN > Package Installer.
* Done.
##### Fixing PS2 Games

* You might've noticed that the wiki has mentions for fixes or using different emus for PS2-FPKG.
* Fixes are found here:
   * <a href="https://www.psx-place.com/threads/research-ps2-emulator-configuration-on-ps4.16131/page-147"> PS2 Config Files </a>
   * Use search bar (must be signed-in), search for your game and make sure you check "In this thread only".
   * You will find mentions of what emulator to use, and CLI + LUA fixes.
   * CLI are .txt files and LUA are .lua files. Both can be done with any notepad editor (make sure you lua files aren't .lua.txt!)
* Emus can be found here:
   * <a href="https://github.com/florinsdistortedvision/ps2-classics-emus"> PS2 Classics Emus </a>
   * Simply unarchive the files and put the emus folder in PS2-FPKG directory. Once you open the program, you will have a drop down list in emulator section.

#### PSP

* With the release of PSP Classics on PS Plus, new emulators have been developed by Sony.
* Before attempting, check compatibility list here (if a game is not on the list, feel free to test it):
<a href="https://www.psx-place.com/threads/psp-fpkg-v1-0-1-play-psp-games-with-the-ps-plus-emulator.37947/"> PSP Compatibility List </a>
* Download and extract PSP-FPKG:
   * <a href="https://www.psx-place.com/threads/psp-fpkg-v1-0-1-play-psp-games-with-the-ps-plus-emulator.37947/"> PSP-FPKG v1.0.1 </a>
* Download your favourite PSP rom. Make sure it is either in a .ISO file format.
* Launch PSP-FPKG v1.0.1. In the Disc section select the .ISO file.
* Rename the tile if it hasn't updated to the game name. Add your own NP Title if it hasn't updated.
* You can select a custom Icon & Background image to make it prettier on the homescreen and when you launch it.
   * Icon resolution must be 512x512
   * Background resolution must be 1920x1080
* Select Create fPKG and wait until it's finished.
* Add the created pkg to the root of a USB drive and install it on your PS4 by navigating to Settings > GoldHEN > Package Installer.
* Done.

##### Fixing PSP Games

* You might've noticed that the wiki has mentions for fixes or using different emus for PSP-FPKG.
* Fixes are found here:
   * <a href="https://www.psx-place.com/threads/psp-fpkg-psp-compatibility-on-ps4-user-submitted-test-results.37952/"> PSP Config Files </a>
   * Use search bar (must be signed-in), search for your game and make sure you check "In this thread only".
   * You will find mentions of what emulator to use, and CLI + LUA fixes.
   * CLI are .txt files and LUA are .lua files. Both can be done with any notepad editor (make sure you lua files aren't .lua.txt!)
* PSPHD - Texture Dumping and Replacement can be found here:
   * <a href="https://www.psx-place.com/threads/tutorial-psphd-texture-dumping-and-replacement.38771/"> PSPHD </a>

#### SEGA SATURN

* Before attempting, check compatibility list here (if a game is not on the list, feel free to test it):
<a href="https://docs.google.com/spreadsheets/u/0/d/1X4iLL8J5sPMlxr_XbfZ-3f21IF9ni-otn2wwl-4hzsk/htmlview#"> Sega Saturn Compatibility List </a>
* Download and extract SATURN-FPKG:
   * <a href="https://www.psx-place.com/threads/update-v1-1-saturn-fpkg-convert-saturn-games-into-ps4-fpkgs.36031/"> SATURN FPKG </a>
   * [Backup mirror](/backupfiles/SATURN-FPKG_v1.1.7z)
* Download your favourite Saturn rom. Make sure it is either in a .bin and .cue file format.
* Launch SATURN-FPKG. In the Disc section select the .bin file.
* Rename the tile if it hasn't updated to the game name. Add your own NP Title if it hasn't updated.
* You can select a custom Icon & Background image to make it prettier on the homescreen and when you launch it.
   * Icon resolution must be 512x512
   * Background resolution must be 1920x1080
* Select Create fPKG and wait until it's finished. For multi-disc games you must make new pkg but keeping the same NP Title. When you're done playing a game that requires one disc, save then install and override it with the new pkg.
* Add the created pkg to the root of a USB drive and install it on your PS4 by navigating to Settings > GoldHEN > Package Installer.
* Done.


### Emulator Ports

* For the majority of the systems, RetroArch is the recommended option.
* Note that RetroArch has been unofficially ported, thus not all cores from PC version might be available.
* Games can be loaded via a USB drive formatted as exFAT. The roms can be placed in a folder.
* RetroArch and it's Core Installer can be found here: <a href="https://www.psx-place.com/threads/retroarch-ps4-r4-released-21-new-cores-added-ppsspp-mame-2015-new-dynarec-support-flycast.30137/"> RetroArch </a>
* Alternatively, it can also be found via the 
[Homebrew Store](hb-store.md)
* Order of installation: Retroarch Core Installer > Ok to install every core and then RetroArch.
* Done.

## Troubleshooting

 * I built a pkg file with its tool but game either crashes or black screens. In this case the game is not supported.
