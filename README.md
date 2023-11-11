# SF2000Scrapped
Scrapped image for SF2000 + Multicore

****TODO: PENDING PROPER DOCUMENTATION****

# What do you need to start with

1. Latest release from SF2000 multicore: https://github.com/madcock/sf2000_multicore_cores/releases/tag/v0.08
2. An SD card formatted to FAT32 (Use https://github.com/inconsistent-dg/guiformat to properly format cards bigger than 32GB)
3. You need to provide your own roms, in No-Intro (https://no-intro.org/) naming convention

# How to create your own image

1. Download and unzip the release (https://github.com/johnnyonno/SF2000Scrapped/releases/download/v1.0/SF2000Scrapped_v1.0.zip) to the root of an empty SD card formatted in FAT32
2. Download and unzip the latest SF2000 multicore (https://github.com/madcock/sf2000_multicore_cores/releases/tag/v0.08) to somewhere else in your computer
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
3. Copy all bios files from ORIGINALSD/bios to SDCARD/bios (gba_bios.bin, neogeo.zip, etc.)
4. Provide needed extra bios files (syscard3.pce, disksys.rom, etc.)
5. Copy your UNZIPPED No-Intro named ROMS to SDCARD/ROMS
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
- ROMS/ngp - NeoGeo Pocket roms, ngc extension (you may need to rename some files here)
- ROMS/pce - PC Engine roms, pce extension
- ROMS/sfc - SNES roms, sfc extension
- ROMS/sfd - SNES roms, sfd extension
- ROMS/sg - Sega SG-1000 roms, sg extension
- ROMS/sms - Master System roms, sms extension

Now all your roms should work on the device, with beautiful boxart, using the stock menu.

You can use Tadpole (https://github.com/EricGoldsteinNz/tadpole) to rename/delete the stubs you don't need (Note: screenshots won't be shown on Tadpole, but they'll show on device).

# Thanks to all this amazing people

@osaka, @kobil, @adcockm on Discord, for the amazing multicore (https://github.com/madcock/sf2000_multicore)

@ericgoldstein @jasongrieves, for the amazing Tadpole (https://github.com/EricGoldsteinNz/tadpole)

@vonmillhausen, for the amazing docs (https://github.com/vonmillhausen/sf2000)

@dteyn, for the amazing ZFBTool (https://github.com/Dteyn/ZFBTool)

  
