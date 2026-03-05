# BRAL -- Better Rayman Anniversary Launcher

A better game launcher for Rayman 30th Anniversary Edition, based on
MrEliptik's game_launcher.\
This is a half-assed attempt to enjoy the original games with their
original soundtrack.

------------------------------------------------------------------------

I made a detailed explaination how to set it up.\
Just Click on the picture below.

<div align="center">
  <a href="https://www.youtube.com/watch?v=DBh0RKSUlik">
    <img src="https://img.youtube.com/vi/DBh0RKSUlik/maxresdefault.jpg" alt="RESTORING the Soundtrack of Rayman 30th Anniversary Edition" style="width:100%; max-width:600px;">
  </a>
</div>

------------------------------------------------------------------------

## Requirements

**IN ORDER TO USE THIS, YOU NEED TO OWN A LEGITIMATE COPY OF "Rayman
30th Anniversary Edition" ON PC!**\
**I DO NOT CONDONE PIRACY, EVEN IF UBISOFT DESERVED IT!**\
**THIS GIT REPOSITORY THEREFORE DOES NOT CONTAIN ROMS OR ANY ASSETS MADE
BY UBI!**\
**YOU HAVE TO EXTRACT THEM YOURSELF!**

------------------------------------------------------------------------

## Tools Required to Decompress `assets.pie`

https://github.com/Masquerade64/Cowabunga

Paste this into a PowerShell window

    ./cowabunga64.exe -c 0x64DA7B23 assets.pie assets.zip

Key discovered by:\
https://github.com/henrygame3

------------------------------------------------------------------------

## PSX .bps Patch

A `.bps` patch for the PSX version can be found here:

https://gamebanana.com/sounds/86151

It also contains a guide explaining how to patch the PSX ROM.

------------------------------------------------------------------------

## Included Tools / Emulators

MrEliptik's game_launcher\
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

## Regarding MrEliptik's game_launcher

To add games to the launcher, place executable files in the `games`
folder.

You must create a `.bat` file that points to the emulator executable and
the ROM.

The Command inside the `.bat` should look like this:
    `start "" "Path to Emulator EXE" "Path to Rom"`

The launcher cannot run `.bat` files. For this reason, a `bat2exe`
script is included.

It is provided as a `.bat` file. Drag your `.bat` file onto it, and it
will generate an `.exe` that performs the same task.

A Python version is also included, featuring a more convenient user
interface for ease of use.
