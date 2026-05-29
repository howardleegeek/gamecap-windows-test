# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use the one-click installer:

[GameCap-OneClick-Setup-v0.1.1.cmd](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.1/GameCap-OneClick-Setup-v0.1.1.cmd)

Download it, double-click it, and it will automatically download the full package, install it under the Windows user directory, create a desktop shortcut, and open GameCap.

## Full Package

Manual full package:

[gamecap-windows-test-v0.1.1.zip](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.1/gamecap-windows-test-v0.1.1.zip)

SHA-256:

```text
f2b8d3141811628417e2ea94145e09fbc353661fcb05d3fcd21d6fe7bdb7a101
```

## Tester Steps After Install

1. Start OBS Studio with WebSocket enabled on port `4455`.
2. Start Minecraft Java `1.20.1` with a Fabric Loader `1.20.1` profile.
3. Open GameCap from the desktop shortcut.
4. Click `1. 安装/检查 Fabric Mod`.
5. Click `3. 检查 OBS / 服务`.
6. Click `开始 5 分钟录制`.

The package bundles Windows `node.exe` and `ffprobe.exe`; testers do not need Node.js, npm, or command-line usage.
