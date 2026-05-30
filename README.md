# GameCap Windows Test

Latest Windows tester build: v0.1.17

Direct download:
https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.17/GameCap-Full-Setup-v0.1.17.exe

SHA-256:
1292231169d8b30f5b462aa701b0e091a3b2b63300c8f6a859cde93540930cc5

## Tester flow

1. Download GameCap-Full-Setup-v0.1.17.exe.
2. Double-click the EXE.
3. GameCap opens and starts automatically.
4. If Minecraft Launcher is already logged in, GameCap attempts to press Play automatically.
5. If Minecraft does not pop out, click Play once in the official Launcher.
6. Enter a world. GameCap automatically starts a 5-minute recording after the world is detected.
7. Click 打开结果 to return the session files.

## What is bundled

- Portable OBS Studio runtime, already configured for local recording and WebSocket port 4455.
- Windows Node.js runtime.
- ffprobe runtime.
- GameCap Minecraft Fabric Mod.
- Fabric API for Minecraft 1.21.4.
- Local capture client and local processor.

OBS does not require Twitch login, streaming setup, or a separate OBS install.

## Minecraft requirement

This build targets Minecraft Java Edition with Fabric Loader 0.16.10-1.21.4.

GameCap creates a dedicated GameCap Fabric 1.21.4 profile when possible. Minecraft itself still needs a valid installed and logged-in official Minecraft Launcher account because Minecraft cannot be redistributed or account authorization bypassed inside this package.

## Release page

https://github.com/howardleegeek/gamecap-windows-test/releases/tag/v0.1.17
