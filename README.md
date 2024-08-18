# RetroArch

My personal files and configuration for RetroArch. You just need to copy roms and RetroArch to it.

![alt text](./docs/thumb.png)


## Install

- clone this repo into `D:\Games`
- unzip `RetroArch.zip` into `D:\Games\RetroArch`
- copy roms into `D:\Games\RetroArch\roms`
- copy Gamecube meme cards into `D:\Games\RetroArch\saves\User\GC`
- execute `D:\Games\RetroArch\retroarch.exe`
- Main Menu -> Online updater -> Core updater -> ...

### Cores

- cap32_libretro.dll: Amstrad - CPC
- dolphin_libretro.dll: Nintendo - Game Cube, Wii 
- fbneo_libretro.dll: FBNeo - Arcade Games
- mame_libretro.dll: MAME
- mgba_libretro.dll: Nintendo - Game Boy, Game Boy Color, Game Boy Advance
- mupen64plus_next_libretro.dll: Nintendo - Nintendo 64
- nestopia_libretro.dll: Nintendo - NES
- pcsx_rearmed_libretro.dll: Sony - Playstation
- pcsx2_libretro.dll: Sony - Playstation 2
- picodrive_libretro.dll: Sega - Master System, Mega Drive - Genesis, 32X
- puae_libretro.dll: Commodore - Amiga
- smsplus_libretro.dll: Sega - Game Gear
- snes9x_libretro.dll: Nintendo - SNES

### Configuration

Desktop Menu (F5) -> View -> Settings...

Settings -> Drivers:
- Menu: xmb
- ...restart RetroArch

Settings -> Input -> Hotkey Binds:
- Menu Toggle Gamepad Combo: "Start + Select"

Settings -> User Interface -> Appearance
- Shader Pipeline: OFF
- Color Theme: Background Image
- Background Image: D:\Games\RetroArch\assets\wallpapers\default,png
- Background opacity 90
- Dynamic Background: YES
- Icon Theme: Retro System
- Primary Thumbnails: OFF
- Left Thumbnails: Boxart

## Usage

- Toggle Desktop Menu: F5
- Toggle Menu: F1 or "Start + Select"
- Speed up: SPACE
- Fullscreen: F

---

## Contribution

### Wallpapers for Kdeizy

follow up of [Dynamic Wallpapers. Google link in comments. (Reddit)](https://www.reddit.com/r/RetroArch/comments/mz1zq0/dynamic_wallpapers_google_link_in_comments/)

![alt text](./assets/wallpapers/Amstrad%20-%20CPC.png)

![alt text](./assets/wallpapers/Commodore%20-%20Amiga.png)

![alt text](./docs/contribution-reddit.png)

## FAQ

Why not Atari-ST ? 
- Because Amiga has better sound.

Why not console arcade ports ?
- Because original Arcade system looks better.

Why no system after year 2000 ?
- Beacuse files take up too much space

---

## LINKS

- roms
  - http://www.gametronik.com/
  - http://www.planetemu.net/
    - http://www.planetemu.net/roms/mame-roms
  - https://www.emulatorgames.net/
- RetroArch
  - https://github.com/libretro/libretro-database/tree/master/dat
  - https://github.com/libretro/libretro-database/tree/master/metadat/mame
  - https://github.com/libretro/libretro-database/tree/master/metadat/fbneo-split
  - https://github.com/libretro/fbalpha/tree/master/dats
- bios
  - https://edgeemu.net/browse-mame-S.htm
  - https://archive.org/download/aristmk6_201810
- boards infos
  - https://www.system16.com/
- Amiga
  - sound effects
    - https://github.com/libretro/libretro-uae
  - kickstart roms
    - https://www.ikod.se/download/
