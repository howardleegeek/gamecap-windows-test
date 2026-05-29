# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use the EXE installer:

[GameCap-Setup-v0.1.3.exe](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.3/GameCap-Setup-v0.1.3.exe)

Download it, double-click it, and it will automatically download the full package, verify SHA-256, install it under the Windows user directory, create a desktop shortcut, and open GameCap.

This version fixes Windows PowerShell UTF-8 parsing for Chinese UI text.

Installer SHA-256:

```text
c972a78559294531cf1b17e57e623e2239f118d887b48bb94acf90b168a9fbb0
```

## Full Package

Manual full package:

[gamecap-windows-test-v0.1.3.zip](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.3/gamecap-windows-test-v0.1.3.zip)

Full package SHA-256:

```text
6ccf37405391ad85e68e4ca60c9d8768a0467117b82ff95fc60751e7af311328
```

## Tester Steps After Install

1. Start OBS Studio with WebSocket enabled on port `4455`.
2. Start Minecraft Java `1.20.1` with a Fabric Loader `1.20.1` profile.
3. Open GameCap from the desktop shortcut.
4. Click `1. 安装/检查 Fabric Mod`.
5. Click `3. 检查 OBS / 服务`.
6. Click `开始 5 分钟录制`.

The package bundles Windows `node.exe` and `ffprobe.exe`; testers do not need Node.js, npm, or command-line usage.
