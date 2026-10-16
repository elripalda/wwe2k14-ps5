# WWE 2K14 for PS5

**WWE 2K14 (Xbox 360) running natively on a jailbroken PS5**, at up to 1440p.

> ### Built on WWE 2K14 Recomp by PromethenDev
> This port is based on **[WWE 2K14 Recomp](https://github.com/PromethenDev/wwe2k14-recomp)**, PromethenDev's native recompilation of WWE 2K14 for PC. His work is the backbone of this project: this release takes it to the PS5. Go check out and support the original project.

## What's in it
- 720p (the original) or 1440p, 60 fps in matches, 30 in entrances like the console
- PlayStation button prompts throughout the game, with DualSense controller pictures (or the Xbox originals, if you prefer)
- Your own entrance music: songs in the `Music` folder show up under Create An Entrance > USER PLAYLIST
- A hub made for the DualSense: start the game, change settings, back up and restore saves, install DLC
- The game's 41 achievements as PS5-style trophies, with a popup in the game
- DLC and saves

## What you need
- A jailbroken PS5 that runs homebrew apps from `/data/homebrew/`
- Your **own** copy of WWE 2K14 for Xbox 360 and its Title Update 1.0.3. No game files are included.

## Install
1. Download `PPSA92014.zip` from [Releases](../../releases) and copy the `PPSA92014` folder to `/data/homebrew/` on your PS5.
2. Copy everything in your WWE 2K14 game folder into its `Assets` folder, with the title update's `default.xexp`:

```
/data/homebrew/PPSA92014/Assets/default.xex
/data/homebrew/PPSA92014/Assets/default.xexp
/data/homebrew/PPSA92014/Assets/pac/...
```

3. DLC: put the package files in `/data/homebrew/PPSA92014/DLC/` (or on a USB drive) and install them from the hub's DLC page.
4. Music: put `.mp3`, `.ogg`, `.flac` or `.wav` files in `/data/homebrew/PPSA92014/Music/`.

Launch it from your homebrew launcher. The hub opens first and checks your game files: press START GAME.

## Known issues
- Online features don't work (the Xbox LIVE servers are gone).
- The game shows the first 19 letters of a song's name, so keep the start of each one different.

## Credits
- **[PromethenDev](https://github.com/PromethenDev)**: [WWE 2K14 Recomp](https://github.com/PromethenDev/wwe2k14-recomp), the recompilation and game fixes this port is built on
- **[elripalda](https://github.com/elripalda)**: the PS5 port, the hub and the PlayStation buttons
- **[HollywoodAkeem](https://github.com/HollywoodAkeem)**: [rexglue-sdk-yukes](https://github.com/HollywoodAkeem/rexglue-sdk-yukes), the runtime fork for Yuke's games
- **[ReXGlue](https://github.com/rexglue/rexglue-sdk)**: the static recompiler and runtime; **[Xenia](https://github.com/xenia-project/xenia)**: the emulator its code comes from

*An unofficial fan project, not affiliated with or endorsed by WWE, 2K, Yuke's, Visual Concepts, Microsoft or Sony. No game files are included.*
