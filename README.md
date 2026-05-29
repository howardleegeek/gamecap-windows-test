# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use the EXE installer:

[GameCap-Setup-v0.1.5.exe](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.5/GameCap-Setup-v0.1.5.exe)

Download it, double-click it, and it will automatically download the full package, verify SHA-256, install it under the Windows user directory, create a desktop `GameCap-Start.cmd` launcher, and open GameCap.

This version avoids reinstall failure when an older GameCap `node.exe` is still running by installing into a new timestamped folder instead of deleting the old install directory.

Installer SHA-256:

```text
5c600ae015bb3d164f075d5dbdb835a89b35f9ecf6694d7b993a82e5f862fa4b
```

## Full Package

Manual full package:

[gamecap-windows-test-v0.1.5.zip](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.5/gamecap-windows-test-v0.1.5.zip)

Full package SHA-256:

```text
0aa39696650b7c2b02c7371ba245e7ce13df905cd2444335eac22f835c7942f6
```

## Tester Steps After Install

1. Start OBS Studio with WebSocket enabled on port `4455`.
2. Start Minecraft Java `1.20.1` with a Fabric Loader `1.20.1` profile.
3. Open GameCap from `GameCap-Start.cmd` on the desktop.
4. Click `1. 安装/检查 Fabric Mod`.
5. Click `3. 检查 OBS / 服务`.
6. Click `开始 5 分钟录制`.

The package bundles Windows `node.exe` and `ffprobe.exe`; testers do not need Node.js, npm, or command-line usage.
