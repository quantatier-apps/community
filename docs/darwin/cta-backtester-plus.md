# Backtest Pro

Part of **Quantatier · Darwin**

Backtest Pro is a Darwin app for executing CTA backtest tasks submitted from Cloud. It processes task batches using local historical data, saves task results, and returns execution status and reports to Cloud.

## Before you begin

Have Backtest Pro installed and enabled in **Application center**, with valid authorization, and connect Darwin to Cloud. Use a completed strategy version in Cloud; Cloud prepares that version for the connected device. Confirm that the required historical data is available there.

## Basic workflow

1. Prepare the supported backtest task from the completed strategy version in Cloud and confirm that the connected Darwin device has the required historical data.
2. Submit the task. In Darwin, open **Application center** and use the app's **View Cloud tasks** action to open **Cloud tasks** and follow execution and result delivery.
3. Review completed results in Cloud. When a task fails, inspect its status and relevant logs before correcting the inputs and submitting another task.

## Results and task status

Successfully completed tasks retain daily results even when there are no trades. A task that encounters a strategy execution error is marked as failed; its partial output is not saved as a completed report.

## Common questions

Accepted batches can continue executing during a Cloud disconnection; reconnect Darwin for status and result delivery. Keep Darwin running: after a restart, unfinished batches are marked interrupted and are not automatically replayed. New batch acceptance requires valid authorization.

For help, follow [Support](../../SUPPORT.md) and mention **Darwin / Backtest Pro**.

[Back to Quantatier](../../README.md)
