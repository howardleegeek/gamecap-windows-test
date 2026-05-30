# GameCap Windows Test

Latest Windows tester build: v0.1.16

Direct download:
https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.16/GameCap-Full-Setup-v0.1.16.exe

SHA-256:
a3ce974d099c8d709f9c6b22b5442ac90452d3529481e1d2baf1f209fcb71276

## Tester flow

1. Download GameCap-Full-Setup-v0.1.16.exe.
2. Double-click the EXE.
3. GameCap installs to the Windows user folder and opens automatically.
4. GameCap prepares the GameCap Fabric 1.21.4 Minecraft profile, opens bundled OBS, opens Minecraft Launcher, starts the local processor, and waits for world detection.
5. If Minecraft Launcher is already logged in, GameCap attempts to trigger Play automatically.
6. If Minecraft does not pop out automatically, log in once or click Play in the official Launcher.
7. Enter a world. GameCap automatically starts a 5-minute recording after the world is detected.

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

GameCap creates a dedicated GameCap Fabric 1.21.4 profile in launcher_profiles.json or launcher_profiles_microsoft_store.json when possible. Minecraft itself still needs a valid installed and logged-in official Minecraft Launcher account because Minecraft cannot be redistributed or account authorization bypassed inside this package.

## Important behavior

Recording waits until the Mod reports that the player is inside a world. This avoids recording too early while the Minecraft launcher or menu is still open.

Each install uses a fresh timestamped folder under LOCALAPPDATA\GameCapMinecraftCapture, which avoids failures caused by old locked node.exe or OBS files.

## Release page

https://github.com/howardleegeek/gamecap-windows-test/releases/tag/v0.1.16
