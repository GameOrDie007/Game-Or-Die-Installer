# Game Or Die Installer

One download for every Game Or Die VR mod. Pick a game, press **INSTALL**, then **PRESS START**.

**[Download Game Or Die Installer](https://github.com/GameOrDie007/Game-Or-Die-Installer/releases/latest/download/Game.Or.Die.Installer.exe)**

## Installing

1. Download the installer and double click it. There is nothing to unzip.
2. Windows may show "Windows protected your PC", because the installer is not signed with a paid
   certificate. Click **More info**, then **Run anyway**.
3. Pick a game on the left and press **INSTALL**. The installer finds your copy of the game
   (Steam, GOG or a disc install), puts the VR files in a VR folder beside it, and adds a desktop
   shortcut and a Steam library entry.
4. Start Virtual Desktop or SteamVR, put your headset on, and press **PRESS START**.

The installer keeps itself up to date and shows **UPDATE** when a game has a new version. Your
saves and settings are kept through every update and uninstall.

## The games

Every Game Or Die VR mod is in it, and new ones show up by themselves as they come out. A few of
the older games download with one click and install with their own Setup for now; each one moves to
one-click install with its next update. Every game's own page on GitHub has its source, its release
notes and how to install it by hand.

## Something not working?

Press **logs** in the installer. It makes one zip on your desktop with the game's logs and a short
description of your PC. Open an issue on the game's GitHub page with the zip and a line about what
happened.

## For tools and hubs

The installer takes the same switches as every Game Or Die `Setup.bat`, after the game's name:

```
"Game Or Die Installer.exe" forsaken -Quiet -Json [-GamePath "<folder>"] [-AddToSteam] [-CloseSteam]
"Game Or Die Installer.exe" descent -Detect -Json
"Game Or Die Installer.exe" descent -Uninstall -Quiet
```

Exit codes: 0 done, 1 nothing could be installed, 2 error.

## Supporting the mods

The mods are free, always. If you'd like to support them, I'm on
[Patreon](https://www.patreon.com/GameOrDie). Videos of every game and everything else I make are
at [gameordie.net](https://gameordie.net).

The installer's lettering is the Press Start 2P font, by The Press Start 2P Project Authors, under
the SIL Open Font License (`licenses/`).
