# SF2000Scrapped
Scrapped image for SF2000 + Multicore

****TODO: PENDING PROPER DOCUMENTATION****

# What do you need to start with

1. Latest release from SF2000 multicore: https://github.com/madcock/sf2000_multicore_cores/releases
2. An SD card formatted to FAT32 (Use https://github.com/inconsistent-dg/guiformat to properly format cards bigger than 32GB)
3. You need to provide your own roms, in No-Intro (https://no-intro.org/) naming convention

# How to create your own image

1. Download and unzip the release (https://github.com/johnnyonno/SF2000Scrapped/releases/download/v1.0/SF2000Scrapped_v1.0.zip) to the root of an empty SD card formatted in FAT32
2. Download and unzip the latest SF2000 multicore (https://github.com/madcock/sf2000_multicore_cores/releases) to somewhere else in your computer
- copy everything from MULTICORE/bios to SDCARD/bios
- copy everything from MULTICORE/cores/config to SDCARD/cores/config
- copy everything from MULTICORE/cores/sega to SDCARD/cores/32x
- copy everything from MULTICORE/cores/a26 to SDCARD/cores/a26
- copy everything from MULTICORE/cores/nes to SDCARD/cores/fds
- copy everything from MULTICORE/cores/gb to SDCARD/cores/gb
- copy everything from MULTICORE/cores/gba to SDCARD/cores/gba
- copy everything from MULTICORE/cores/gb to SDCARD/cores/gbc
- copy everything from MULTICORE/cores/sega to SDCARD/cores/gg
- copy everything from MULTICORE/cores/lnx to SDCARD/cores/lnx
- copy everything from MULTICORE/cores/m2k to SDCARD/cores/m2k
- copy everything from MULTICORE/cores/sega to SDCARD/cores/md
- copy everything from MULTICORE/cores/nes to SDCARD/cores/nes
- copy everything from MULTICORE/cores/ngpc to SDCARD/cores/ngp
- copy everything from MULTICORE/cores/pce to SDCARD/cores/pce
- copy everything from MULTICORE/cores/snes to SDCARD/cores/sfc
- copy everything from MULTICORE/cores/snes02 to SDCARD/cores/sfd
- copy everything from MULTICORE/cores/sega to SDCARD/cores/sg
- copy everything from MULTICORE/cores/sega to SDCARD/cores/sms
- copy everything from MULTICORE/cores/wswan to SDCARD/cores/wsc
3. Copy all bios files from ORIGINALSD/bios to SDCARD/bios (gba_bios.bin, neogeo.zip, etc.)
4. Provide needed extra bios files (syscard3.pce, disksys.rom, etc.)
5. Copy your Arcade roms from ORIGINALSD/ARCADE/bin to SDCARD/ARCADE/bin
6. Copy your UNZIPPED No-Intro named ROMS to SDCARD/ROMS
- ROMS/32x - Sega 32x roms, 32x extension
- ROMS/a26 - Atari 26000 roms, a26 extension
- ROMS/fds - Famicom Disk System roms, fds extension
- ROMS/gb - Game Boy roms, gb extension
- ROMS/gba - Game Boy Advance roms, gba extension
- ROMS/gbc - Game Boy Color roms, gbc extension
- ROMS/gg - Game Gear roms, gg extension
- ROMS/lnx - Atari Lynx roms, lnx extension
- ROMS/m2k - Mame2000 roms, zip extension
- ROMS/mds - Mega Drive roms, md extension
- ROMS/nes - NES roms, nes extension
- ROMS/ngp - NeoGeo Pocket roms, ngc extension (you may need to rename some files here, for non-color NeoGeoPocket roms)
- ROMS/pce - PC Engine roms, pce extension
- ROMS/sfc - SNES roms, sfc extension
- ROMS/sfd - SNES roms, sfc extension
- ROMS/sg - Sega SG-1000 roms, sg extension
- ROMS/sms - Master System roms, sms extension
- ROMS/wsc - WonderSwan roms, swc extension (you may need to rename some files here, for non-color WonderSwan roms)

# What will you find here

Now all your roms should work on the device, with beautiful boxart, using the stock menu.

You can use Tadpole (https://github.com/EricGoldsteinNz/tadpole) to rename/delete the stubs you don't need (Note: screenshots won't be shown on Tadpole, but they'll show on device).

- Original NES Folder, now will have NES roms (prefixed with nes)) and FDS roms (prefixed with fds)) -> NES SYSTEM
- Original SNES Folder, now will have SNES roms (prefixed with sfc) will run on Snes9x 2005, prefixed with 02) will run on Snes9x 2002) -> SNES SYSTEM
- Original GB Folder, now will have GB, GBC, GBA roms (prefixed by gb) gbc) gba) respectively) -> GAME BOY SYSTEM
- Original GBC Folder, now will have Atari2600, NeoPocket, Lynx, WonderSwan roms (prefixed by a26) ngp) lnx) wsc) respectively) -> MISC SYSTEMS
- Original GBA Folder, now will have PC Engine roms (prefixed by pce)) -> PCE SYSTEM
- Original MegaDrive Folder, now will have SG-1000, Master System, MegaDrive, 32x, GameGear roms (prefixed by sg) sms) md) 32x) gg) respectively) -> SEGA SYSTEM
- Original Arcade Folder, now will have original Arcade roms and Mame2000 roms (prefixed by m2k)) -> ARCADE SYSTEM

# Notes & Caveats

- You can use Tadpole to choose "shortcut roms" too (the 4 ones found on the main page of a system), even change the image (you'll need to provide your own images here though).
- Not all games from the romsets are available as ZFB files; only the ones I could scrape from (https://www.screenscraper.fr/)
- If you have a ZFB file that doesn't have its corresponding rom file in the proper roms directory, it will hang on "Loading" screen: power cycle your device to exit.
- You can rename the ZFB files as you please: you can do it with Tadpole directly, or directly on the Filesystem. If you do it from the Filesystem, you'll need to rebuild the rom list using Tadpole (just load tadpole and select the system from the combo-box at the top).
- DON'T TRY TO KEEP FULL ROMSETS ON YOUR DEVICE! All the files are provided here FOR YOU TO TRIM THE SET DOWN TO YOUR PREFERENCES! 

# Thanks to all this amazing people

@osaka, @kobil, @adcockm on Discord, for the amazing multicore (https://github.com/madcock/sf2000_multicore)

@ericgoldstein @jasongrieves, for the amazing Tadpole (https://github.com/EricGoldsteinNz/tadpole)

@vonmillhausen, for the amazing docs (https://github.com/vonmillhausen/sf2000)

@dteyn, for the amazing ZFBTool (https://github.com/Dteyn/ZFBTool)

  
