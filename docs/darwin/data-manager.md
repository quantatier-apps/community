# Data Manager

Part of **Quantatier · Darwin**

Data Manager helps you inspect and maintain local historical market data, including supported CSV imports and exports.

## Before you begin

Have the app installed and enabled, with the local database configured. Downloading history also requires a configured data service, a working connection, and the relevant data access.

## Basic workflow

1. Open Data Manager and inspect the available instruments, intervals, and date coverage.
2. Select the historical data you want to review or maintain.
3. For CSV exchange, use the supported import or export controls and check the resulting data coverage.
4. To obtain history through a data service, confirm its configuration and access before requesting the required data.

Imported or downloaded data can support [local backtesting](local-backtesting.md). For recording incoming market data, see [Data Recorder](data-recorder.md).

## Common questions

If data is missing, check the instrument, interval, date range, and database configuration. If a download fails, check the data service and its access requirements. Data Manager does not provide market-data rights by itself.

## Updates and help

See the [original product note](https://github.com/quantatier-apps/community/discussions/3). For help, follow [Support](../../SUPPORT.md) and mention **Darwin / Data Manager**.

[Back to Quantatier](../../README.md)
