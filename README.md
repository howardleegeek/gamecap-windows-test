# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use the EXE installer:

[GameCap-Setup-v0.1.7.exe](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.7/GameCap-Setup-v0.1.7.exe)

Download it and double-click it. It will download the full package, verify SHA-256, install under the Windows user directory, create a desktop `GameCap-Start.cmd` launcher, open GameCap, then GameCap will try to auto-open OBS Studio and Minecraft Launcher.

This version is the foolproof Windows tester build for Minecraft Java `1.21.4` + Fabric Loader `0.16.10`. It bundles `fabric-api-0.119.4+1.21.4.jar` and the rebuilt GameCap Fabric mod.

Installer SHA-256:

```text
63c3b581f8da5844082f3003eea7bcbabbdcfdd2c3d502a6d9d7b9d8bb91b59d
```

## Full Package

Manual full package:

[gamecap-windows-test-v0.1.7.zip](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.7/gamecap-windows-test-v0.1.7.zip)

Full package SHA-256:

```text
22a1e7035d18b6a5cd682ffe58e84e9cdcf9de3c0e5743d1be1954013b3a9c1c
```

## Tester Steps After Install

1. Run `GameCap-Setup-v0.1.7.exe`.
2. GameCap auto-installs the mod jars, starts the local Processor, opens OBS Studio, and opens Minecraft Launcher.
3. In Minecraft Launcher, choose `fabric-loader-1.21.4`, click Play, and enter a world.
4. Return to GameCap and click `我已进入世界，开始 5 分钟录制`.
5. After recording, click `打开录制结果` and `打开处理结果` and send the output back.

If OBS or Minecraft does not open automatically, click `一键准备：打开 OBS + 打开 Minecraft` inside GameCap.

The package bundles Windows `node.exe`, Windows `ffprobe.exe`, GameCap Fabric mod, and Fabric API; testers do not need Node.js, npm, or command-line usage.
