# GameCap Windows Test Package

Windows test build for Minecraft Fabric capture.

## Download

The release package is `gamecap-windows-test-v0.1.0.zip`.

SHA-256:

```text
b042a592942dfe2548a9b6f9e9d1570e3b18cb12223c25a686264df0bb176bc9
```

## Tester Steps

1. Download and unzip `gamecap-windows-test-v0.1.0.zip`.
2. Double-click `GameCap一键启动.bat`.
3. Click `1. 安装/检查 Fabric Mod`.
4. Start OBS Studio with WebSocket enabled on port `4455`.
5. Start Minecraft Java `1.20.1` with a Fabric Loader `1.20.1` profile.
6. Click `3. 检查 OBS / 服务`.
7. Click `开始 5 分钟录制`.

The package bundles Windows `node.exe` and `ffprobe.exe`; testers do not need Node.js, npm, or command-line usage.
