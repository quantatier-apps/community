# CTA Backtester Plus

Part of **Quantatier · Darwin**

CTA Backtester Plus runs Cloud-submitted backtest batches on your Darwin device and returns results for Cloud analysis. Use it when you want to organize research in Cloud while executing backtests against locally available strategies and historical data.

## Before you begin

Have CTA Backtester Plus installed and enabled in **Application center**, with valid authorization, and connect Darwin to Cloud. Use a completed strategy version in Cloud; Cloud prepares that version for the connected device. Confirm that the required historical data is available there.

## Basic workflow

1. Prepare the supported backtest task from the completed strategy version in Cloud and confirm that the connected Darwin device has the required historical data.
2. Submit the task, then use **Cloud tasks** in Darwin to follow its execution and result delivery.
3. Review completed results in Cloud. When a task fails, inspect its status and relevant logs before correcting the inputs and submitting another task.

In Darwin, the Plus card's **View Cloud tasks** action opens the task-management page. It does not open the native desktop backtesting form. For the standard graphical workflow that you configure and run locally, see [Local Backtesting](local-backtesting.md).

## Common questions

Accepted batches can continue executing during a Cloud disconnection; reconnect Darwin for status and result delivery. Keep Darwin running: after a restart, unfinished batches are marked interrupted and are not automatically replayed. New batch acceptance requires valid authorization.

For help, follow [Support](../../SUPPORT.md) and mention **Darwin / CTA Backtester Plus**.

[Back to Quantatier](../../README.md)
