# Darwin Downloads

Download Darwin and optional apps for **Apple Silicon Macs running macOS 15 or later**.

| Product | Version | Download | Details |
| --- | --- | --- | --- |
| Darwin desktop | 0.21.4 preview | [DMG](https://github.com/quantatier-apps/community/releases/download/darwin-v0.21.4/quantadarwin_client_0.21.4_macos_arm64.dmg) · [SHA-256](https://github.com/quantatier-apps/community/releases/download/darwin-v0.21.4/quantadarwin_client_0.21.4_macos_arm64.dmg.sha256) | [Release notes](https://github.com/quantatier-apps/community/releases/tag/darwin-v0.21.4) |
| Backtest Pro | 0.5.2 preview | [Wheel](https://github.com/quantatier-apps/community/releases/download/backtest-pro-v0.5.2/quantadarwin_ctabacktester_plus-0.5.2-cp310-cp310-macosx_15_0_arm64.whl) · [SHA-256](https://github.com/quantatier-apps/community/releases/download/backtest-pro-v0.5.2/quantadarwin_ctabacktester_plus-0.5.2-cp310-cp310-macosx_15_0_arm64.whl.sha256) | [Release notes](https://github.com/quantatier-apps/community/releases/tag/backtest-pro-v0.5.2) |

## Install Darwin

Download the DMG and its SHA-256 file into the same folder. In Terminal, run `shasum -a 256 -c quantadarwin_client_0.21.4_macos_arm64.dmg.sha256` from that folder. Open the DMG, drag Darwin into Applications, and open it once. This preview is unsigned and unnotarized. macOS may show a security warning or block launch.

## Install Backtest Pro

Requires **Darwin 0.21.4**, an Apple Silicon Mac, and **macOS 15 or later**. Darwin supplies the runtime dependencies, including `psutil`.

1. Install Darwin 0.21.4 and open it once to update its local Python environment. Quit Darwin.
2. Download the Backtest Pro wheel and its SHA-256 file from **Assets** into Downloads.
3. Run these commands in Terminal:

```bash
cd "$HOME/Downloads" &&
shasum -a 256 -c quantadarwin_ctabacktester_plus-0.5.2-cp310-cp310-macosx_15_0_arm64.whl.sha256 &&
"$HOME/Library/Application Support/QuantaDarwin Preview/runtime/bin/python3.10" \
  -I -B -m pip --isolated install --no-index --only-binary=:all: \
  ./quantadarwin_ctabacktester_plus-0.5.2-cp310-cp310-macosx_15_0_arm64.whl &&
"$HOME/Library/Application Support/QuantaDarwin Preview/runtime/bin/python3.10" \
  -I -B -m pip --isolated check
```

4. Reopen Darwin and choose **Modules → Backtest Pro → Enable**. An active Cloud connection and a valid Backtest Pro entitlement are required. Opening Backtest Pro takes you to Cloud Tasks.

## Release history and help

[All GitHub Releases](https://github.com/quantatier-apps/community/releases) · [Local backtesting](docs/darwin/local-backtesting.md) · [Backtest Pro guide](docs/darwin/cta-backtester-plus.md) · [Community Q&A](https://github.com/quantatier-apps/community/discussions/categories/q-a)
