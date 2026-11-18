# Spread Trading

Part of **Quantatier · Darwin**

Spread Trading is an app for trading relationships between multiple instruments. Define spreads from their contract legs, follow calculated spread prices, and run spread algorithms or automated spread strategies.

## Before you begin

Have Spread Trading installed and enabled in **Application center**, with valid authorization. Configure the supported trading interfaces needed for the legs, with the required market-data and trading access. Prepare the leg instruments and your intended spread definition before running an algorithm or strategy.

Spreads composed of exchange arbitrage contracts are not supported.

## Basic workflow

1. Open the enabled Spread Trading app from **Application center** or **Local tools**.
2. Prepare the spread definition using its contract legs, then check the incoming leg data and calculated spread prices.
3. Manage spread algorithms or spread strategies in the Spread Trading window. Review their configuration and monitor their state and logs during execution.

## Common questions

If spread prices are unavailable, check that the required leg instruments have a working market-data connection. If an algorithm or strategy cannot run, check the module authorization, trading connection, configuration, and relevant logs.

For help, follow [Support](../../SUPPORT.md) and mention **Darwin / Spread Trading**.

[Back to Quantatier](../../README.md)
