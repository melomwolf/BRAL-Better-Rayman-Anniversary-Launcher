# BRAL -- Better Rayman Anniversary Launcher

A better game launcher for Rayman 30th Anniversary Edition, based on
MrEliptik's `game_launcher`.\
This is an improvised attempt to enjoy the original games with their
original soundtrack.

------------------------------------------------------------------------

## Requirements

**IN ORDER TO USE THIS, YOU NEED TO OWN A LEGITIMATE COPY OF "Rayman
30th Anniversary Edition" ON PC!**\
**I DO NOT CONDONE PIRACY, EVEN IF UBISOFT DESERVED IT!**\
**THIS GIT REPOSITORY THEREFORE DOES NOT CONTAIN ROMS OR ANY ASSETS MADE
BY UBI!**\
**YOU HAVE TO EXTRACT THEM YOURSELF!**

------------------------------------------------------------------------

## Tools Required to Decompress `asset.pie`

https://github.com/Masquerade64/Cowabunga

The key is:

    0x64DA7B23

Discovered by:\
https://github.com/henrygame3

------------------------------------------------------------------------

## PSX .ips Patch

An `.ips` patch for the PSX version can be found here:

https://gamebanana.com/sounds/86151

It also contains a guide explaining how to patch the ROM yourself.

------------------------------------------------------------------------

## Included Tools / Emulators

MrEliptik's `game_launcher`\
https://github.com/MrEliptik/game_launcher

LIJI32's SameBoy\
https://github.com/LIJI32/SameBoy

mGBA\
https://github.com/mgba-emu/mgba

stenzek's DuckStation\
https://github.com/stenzek/duckstation

Snes9x\
https://github.com/snes9xgit/snes9x

djipi's Virtual Jaguar Rx\
https://github.com/djipi/Virtual-Jaguar-Rx

------------------------------------------------------------------------

## Why No DOS Version?

Because Rayman Redemption (by Ryemanni) is significantly better.\
https://gamejolt.com/games/raymanredemption/340532

------------------------------------------------------------------------

## Regarding MrEliptik's `game_launcher`

To add games to the launcher, place executable files in the `games`
folder.

You must create a `.bat` file that points to the emulator executable and
the ROM.

The launcher cannot run `.bat` files. For this reason, a `bat2exe`
script is included.

It is provided as a `.bat` file. Drag your `.bat` file onto it, and it
will generate an `.exe` that performs the same task.

A Python version is also included, featuring a more convenient user
interface for ease of use.
