# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use the EXE installer:

[GameCap-Setup-v0.1.2.exe](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.2/GameCap-Setup-v0.1.2.exe)

Download it, double-click it, and it will automatically download the full package, verify SHA-256, install it under the Windows user directory, create a desktop shortcut, and open GameCap.

Installer SHA-256:

```text
8f2d11b3e88bf936c1d105c61b81279b6f0f1d164ab7a36794cf462fa61e8a8e
```

## Full Package

Manual full package:

[gamecap-windows-test-v0.1.2.zip](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.2/gamecap-windows-test-v0.1.2.zip)

Full package SHA-256:

```text
56abf7805f7d9b9dcba60dda5567b52ef91097831bd6ecf49dd7e0669920b05b
```

## Tester Steps After Install

1. Start OBS Studio with WebSocket enabled on port `4455`.
2. Start Minecraft Java `1.20.1` with a Fabric Loader `1.20.1` profile.
3. Open GameCap from the desktop shortcut.
4. Click `1. 安装/检查 Fabric Mod`.
5. Click `3. 检查 OBS / 服务`.
6. Click `开始 5 分钟录制`.

The package bundles Windows `node.exe` and `ffprobe.exe`; testers do not need Node.js, npm, or command-line usage.
