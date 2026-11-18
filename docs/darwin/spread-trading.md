# Spread Trading

Part of **Quantatier · Darwin**

Spread Trading supports trading spreads made from multiple contract legs. Its native application covers spread pricing, spread algorithm execution, and spread strategies. Use it when your trading logic depends on the relationship between several instruments.

## Before you begin

Have Spread Trading installed and enabled in **Application center**, with valid authorization. Configure the supported trading interfaces needed for the legs, with the required market-data and trading access. Prepare the leg instruments and your intended spread definition before running an algorithm or strategy.

Spreads composed of exchange arbitrage contracts are not supported.

## Basic workflow

1. Open the enabled Spread Trading app from **Application center** or **Local tools**. Darwin opens the native Spread Trading window.
2. Prepare the spread definition using its contract legs, then check the incoming leg data and calculated spread prices.
3. Use the native window to manage spread algorithms or spread strategies as required by your workflow. Review their configuration and monitor their state and logs during execution.

## Common questions

If spread prices are unavailable, check that the required leg instruments have a working market-data connection. If an algorithm or strategy cannot run, check the module authorization, trading connection, configuration, and relevant logs.

For help, follow [Support](../../SUPPORT.md) and mention **Darwin / Spread Trading**.

[Back to Quantatier](../../README.md)
