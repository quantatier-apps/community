# CTA Strategy

Part of **Quantatier · Darwin**

CTA Strategy runs single-instrument CTA strategies locally. Use it to create strategy instances, initialize them, and manage their running state after preparing and reviewing your strategy.

## Before you begin

Have CTA Strategy installed and enabled in **Application center**, with valid authorization. Have a compatible strategy class available locally, the instrument identifier including its exchange suffix, and the parameters you intend to use. Live trading also requires an appropriately configured and connected trading interface. Prepare any historical data needed for strategy initialization.

## Basic workflow

1. Open CTA Strategy from **Application center** or **Local tools** after enabling it.
2. Choose an available strategy class and create an instance with a unique name, instrument, and strategy parameters.
3. Initialize the instance. Review its initialization state, variables, and logs before starting it. Historical bar initialization can use the configured data source or the local database.
4. Start the initialized instance and monitor its state and logs. Stop the instance before removing it.

Enabling the app does not connect a trading account, initialize a strategy instance, or start trading. These are separate steps.

## Common questions

If a strategy class is missing, confirm that it is available locally. If initialization fails, check the instrument, required history, and log messages. A strategy must finish initialization before it can start.

For help, follow [Support](../../SUPPORT.md) and mention **Darwin / CTA Strategy**.

[Back to Quantatier](../../README.md)
