# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Recommended Download

For non-technical Windows testers, use this full offline EXE installer:

[GameCap-Full-Setup-v0.1.8.exe](https://github.com/howardleegeek/gamecap-windows-test/releases/download/v0.1.8/GameCap-Full-Setup-v0.1.8.exe)

Download it once and double-click it. The full GameCap package is embedded inside this EXE, so there is no second zip/package download during installation.

This version is the foolproof Windows tester build for Minecraft Java `1.21.4` + Fabric Loader `0.16.10`. It bundles Windows Node.js, Windows ffprobe, `fabric-api-0.119.4+1.21.4.jar`, and the rebuilt GameCap Fabric mod.

Installer SHA-256:

```text
2f9dc4f442003231cd89d44e523ad249b94ae83df1cf00237a67bb6f1204eb4f
```

## Tester Steps After Install

1. Run `GameCap-Full-Setup-v0.1.8.exe`.
2. GameCap auto-installs the mod jars, starts the local Processor, opens OBS Studio, and opens Minecraft Launcher.
3. In Minecraft Launcher, choose `fabric-loader-1.21.4`, click Play, and enter a world.
4. Return to GameCap and click `我已进入世界，开始 5 分钟录制`.
5. After recording, click `打开录制结果` and `打开处理结果` and send the output back.

If OBS or Minecraft does not open automatically, click `一键准备：打开 OBS + 打开 Minecraft` inside GameCap.

Testers do not need Node.js, npm, command-line usage, or manual zip extraction.
