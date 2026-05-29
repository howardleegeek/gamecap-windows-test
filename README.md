# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use the EXE installer:

[GameCap-Setup-v0.1.6.exe](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.6/GameCap-Setup-v0.1.6.exe)

Download it, double-click it, and it will automatically download the full package, verify SHA-256, install it under the Windows user directory, create a desktop `GameCap-Start.cmd` launcher, and open GameCap.

This version is the Minecraft Java `1.21.4` + Fabric Loader `0.16.10` compatibility build. It bundles `fabric-api-0.119.4+1.21.4.jar` and the rebuilt GameCap Fabric mod.

Installer SHA-256:

```text
83d5b653e4c15bc65399b92825159b7d94bfda4e0e7014fff70691ea14785b32
```

## Full Package

Manual full package:

[gamecap-windows-test-v0.1.6.zip](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.6/gamecap-windows-test-v0.1.6.zip)

Full package SHA-256:

```text
905d5191accad3a1e5439f4ce0ae1c772a8ffcb4c27dca9c2212e9d546aa40dd
```

## Tester Steps After Install

1. Start OBS Studio with WebSocket enabled on port `4455`.
2. Start Minecraft Java `1.21.4` with Fabric Loader `0.16.10`, usually shown as the `fabric-loader-1.21.4` profile.
3. Open GameCap from `GameCap-Start.cmd` on the desktop.
4. Click `1. 安装/检查 Fabric Mod`.
5. Click `3. 检查 OBS / 服务`.
6. Click `开始 5 分钟录制`.

The package bundles Windows `node.exe`, Windows `ffprobe.exe`, GameCap Fabric mod, and Fabric API; testers do not need Node.js, npm, or command-line usage.
