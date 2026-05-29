# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use this full offline EXE installer:

GameCap-Full-Setup-v0.1.10.exe
https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.10/GameCap-Full-Setup-v0.1.10.exe

Download it once and double-click it. The full GameCap package is embedded inside this EXE, so there is no second zip/package download during installation.

This version bundles OBS Studio portable directly into GameCap and skips the OBS first-run streaming and Twitch setup wizard. Testers do not need to install OBS separately or log in to Twitch. Minecraft itself is not bundled because it requires Microsoft and Mojang licensing plus user login, but GameCap opens Minecraft Launcher and installs the Fabric mod jars.

Installer SHA-256:

4e5b681bcc221fb7df1290e16c7e33bc164f540409fd2a205e6c958c930a4684

## Included

- GameCap capture tool and local Processor.
- Windows Node.js runtime.
- Windows ffprobe.
- OBS Studio 32.1.2 Windows x64 portable runtime.
- GameCap Minecraft Fabric mod.
- Fabric API 0.119.4+1.21.4.

## Tester Steps After Install

1. Run GameCap-Full-Setup-v0.1.10.exe.
2. GameCap auto-installs the mod jars, starts the local Processor, opens bundled OBS Studio, and opens Minecraft Launcher.
3. In Minecraft Launcher, choose fabric-loader-1.21.4, click Play, and enter a world.
4. Return to GameCap and click 我已进入世界，开始 5 分钟录制.
5. After recording, click 打开录制结果 and 打开处理结果 and send the output back.

If OBS or Minecraft does not open automatically, click 一键准备：打开 OBS + 打开 Minecraft inside GameCap.

Testers do not need OBS installation, Node.js, npm, command-line usage, or manual zip extraction.
