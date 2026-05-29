# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use the EXE installer:

[GameCap-Setup-v0.1.4.exe](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.4/GameCap-Setup-v0.1.4.exe)

Download it, double-click it, and it will automatically download the full package, verify SHA-256, install it under the Windows user directory, create a desktop `GameCap-Start.cmd` launcher, and open GameCap.

This version avoids the Windows `WScript.Shell` shortcut creation issue seen in v0.1.3.

Installer SHA-256:

```text
2b839c48c7826e7890fb71e067f9b0ae021eba056ccd317df71bde55dbdec1ad
```

## Full Package

Manual full package:

[gamecap-windows-test-v0.1.4.zip](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.4/gamecap-windows-test-v0.1.4.zip)

Full package SHA-256:

```text
52cee5044418195b49d8742caa3ccadac1e03b2c53425eb3b68f422fb996c3ac
```

## Tester Steps After Install

1. Start OBS Studio with WebSocket enabled on port `4455`.
2. Start Minecraft Java `1.20.1` with a Fabric Loader `1.20.1` profile.
3. Open GameCap from `GameCap-Start.cmd` on the desktop.
4. Click `1. 安装/检查 Fabric Mod`.
5. Click `3. 检查 OBS / 服务`.
6. Click `开始 5 分钟录制`.

The package bundles Windows `node.exe` and `ffprobe.exe`; testers do not need Node.js, npm, or command-line usage.
