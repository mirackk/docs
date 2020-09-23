# FlamIncome Terminal

[FlamIncome Terminal](https://flamincome.finance) provide a terminal UI for professional users

Use the [FlamIncome App](https://app.flamincome.finance) or [Income Page of Flamingo (not available now)](#) if you feel the terminal UI is uncomfortable

# Guide

Users can type commands in FlamIncome Terminal UI for operations.

For more info about all the commands, see [FlamIncome Terminal Reference](https://docs.flamincome.finance/reference/terminal)

## Deposit Token to Flamincome

1. connect wallet

    ```sh
    connect-wallet
    ```

1. for example, deposit `1000` `USDT`, (if you want to deposit other tokens, replace `USDT` to another symbol) (if you want to deposit another amount, replace `1000` to your amount) (if you type `deposit-token-to-vault USDT` without the amount `1000`, the default amount will be your current balance)

    ```sh
    deposit-token-to-vault USDT 1000
    ```

## Withdraw Token from FlamIncome

1. connect wallet

    ```sh
    connect-wallet
    ```

1. for example, withdraw `1000` `fUSDT`, (if you want to withdraw other tokens, replace `USDT` to another symbol) (if you want to withdraw another amount, replace `1000` to your amount) (if you type `withdraw-token-from-vault USDT` without the amount `1000`, the default amount will be your current balance of `fUSDT`)

    ```sh
    withdraw-token-from-vault USDT 1000
    ```