# Darwin Downloads

Download Darwin and optional apps for **Apple Silicon Macs running macOS 15 or later**.

| Product | Version | Download | Details |
| --- | --- | --- | --- |
| Darwin desktop | 0.21.3 preview | [DMG](https://github.com/quantatier-apps/community/releases/download/darwin-v0.21.3/quantadarwin_client_0.21.3_macos_arm64.dmg) · [SHA-256](https://github.com/quantatier-apps/community/releases/download/darwin-v0.21.3/quantadarwin_client_0.21.3_macos_arm64.dmg.sha256) | [Release notes](https://github.com/quantatier-apps/community/releases/tag/darwin-v0.21.3) |
| Backtest Pro | 0.5.1 preview | [ZIP](https://github.com/quantatier-apps/community/releases/download/backtest-pro-v0.5.1/darwin_backtest_pro_0.5.1_macos_arm64.zip) · [SHA-256](https://github.com/quantatier-apps/community/releases/download/backtest-pro-v0.5.1/darwin_backtest_pro_0.5.1_macos_arm64.zip.sha256) | [Release notes](https://github.com/quantatier-apps/community/releases/tag/backtest-pro-v0.5.1) |

## Install Darwin

Download the DMG and its SHA-256 file into the same folder. In Terminal, run `shasum -a 256 -c quantadarwin_client_0.21.3_macos_arm64.dmg.sha256` from that folder. Open the DMG, drag Darwin into Applications, and open it once. This preview is unsigned and unnotarized. macOS may show a security warning or block launch.

## Install Backtest Pro

1. Start with Darwin 0.21.3. Open it once to initialize its environment, then quit it.
2. Download the Backtest Pro ZIP and extract it into Downloads. It includes the compiled app, its `psutil` dependency, checksums, and installation instructions.
3. Run the commands below in Terminal. Adjust the first path if you extracted the ZIP elsewhere.

```bash
cd "$HOME/Downloads/darwin_backtest_pro_0.5.1_macos_arm64" &&
shasum -a 256 -c SHA256SUMS &&
"$HOME/Library/Application Support/QuantaDarwin Preview/runtime/bin/python3.10" \
  -I -B -m pip --isolated install --no-index --only-binary=:all: --find-links . \
  ./quantadarwin_ctabacktester_plus-0.5.1-cp310-cp310-macosx_15_0_arm64.whl &&
"$HOME/Library/Application Support/QuantaDarwin Preview/runtime/bin/python3.10" \
  -I -B -m pip --isolated check
```

4. Reopen Darwin and choose **Modules → Backtest Pro → Enable**. Have an active Cloud connection and a valid Backtest Pro entitlement. Open Backtest Pro to see Cloud Tasks.

## Release history and help

[All GitHub Releases](https://github.com/quantatier-apps/community/releases) · [Local backtesting](docs/darwin/local-backtesting.md) · [Backtest Pro guide](docs/darwin/cta-backtester-plus.md) · [Community Q&A](https://github.com/quantatier-apps/community/discussions/categories/q-a)
