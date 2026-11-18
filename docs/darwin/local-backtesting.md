# CTA Backtester

Part of **Quantatier · Darwin**

CTA Backtester provides a graphical workspace for running supported CTA strategies against local historical data and reviewing results. This workflow can be used without Cloud.

## Before you begin

Have a compatible strategy class and the required historical data available. Use [Data Manager](data-manager.md) to inspect your data coverage. The app must be installed and enabled in **Application center**.

## Basic workflow

1. Open the enabled CTA Backtester app.
2. Select a strategy, instrument, interval, and date range.
3. Configure strategy parameters and backtest settings, including capital, commission, and slippage.
4. Run the backtest and review the available statistics, charts, orders, trades, daily results, and logs.

Parameter optimization controls are available where supported by your product configuration, strategy, and data.

## Common questions

If a strategy is missing, check that its class is available locally. If a backtest has no data or stops unexpectedly, inspect the selected instrument, interval, date range, and logs before rerunning it.

For batches submitted through Cloud, see [CTA Backtester Plus](cta-backtester-plus.md).

## Updates and help

See the [original product note](https://github.com/quantatier-apps/community/discussions/2) and [Announcements](https://github.com/quantatier-apps/community/discussions/categories/announcements) for related changes. For help, follow [Support](../../SUPPORT.md) and mention **Darwin / CTA Backtester**.

[Back to Quantatier](../../README.md)
