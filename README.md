# GameCap Windows Test

Latest Windows tester build: v0.1.15

Direct download:
https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.15/GameCap-Full-Setup-v0.1.15.exe

SHA-256:
2df2c66fa69cbe103b7ffbaedb07b340d626a8b36e75c20b4f73c3118cdc0577

## Tester flow

1. Download .
2. Double-click the EXE.
3. GameCap installs to the Windows user folder and opens automatically.
4. Click .
5. Minecraft Launcher opens. Select , then enter a world.
6. GameCap detects the world and automatically records for 5 minutes.

## What is bundled

- Portable OBS Studio runtime, already configured for local recording and WebSocket port .
- Windows Node.js runtime.
- ffprobe runtime.
- GameCap Minecraft Fabric Mod.
- Fabric API for Minecraft .
- Local capture client and local processor.

OBS does not require Twitch login, streaming setup, or a separate OBS install.

## Minecraft requirement

This build targets Minecraft Java Edition with Fabric Loader .

The tool can copy the Mod files and attempt Fabric profile setup. Minecraft itself still needs a valid installed/logged-in Minecraft Launcher account because Minecraft cannot be redistributed inside this package.

## Important behavior

Recording waits until the Mod reports that the player is inside a world. This avoids recording too early while the Minecraft launcher or menu is still open.

Each install uses a fresh timestamped folder under , which avoids failures caused by old locked  or OBS files.

## Release page

https://github.com/howardleegeek/gamecap-windows-test/releases/tag/v0.1.15
