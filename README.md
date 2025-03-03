# Binance Volitility Trading Bot

## Description
This Binance trading bot analyses the changes in price across all coins on Binance and place trades on the most volatile ones. 
In addition to that, this Binance trading algorithm will also keep track of all the coins bought and sell them according to your specified Stop Loss and Take Profit.



The bot will listen to changes in price accross all coins on Binance. By default we're only picking USDT pairs. We're excluding Margin (like BTCDOWNUSDT) and Fiat pairs

> Information below is an example and is all configurable

- The bot checks if the any coin has gone up by more than 3% in the last 5 minutes
- The bot will buy 100 USDT of the most volatile coins on Binance
- The bot will sell at 6% profit or 3% stop loss
- The bot works with both Main and Testnet


You can follow the [Biance volatility bot guide](https://www.cryptomaton.org/2021/05/08/how-to-code-a-binance-trading-bot-that-detects-the-most-volatile-coins-on-binance/) for a step-by-step walkthrough

## READ BEFORE USE
1. If you use the `TEST_MODE: True` in your config, you will be using REAL money.
2. To ensure you do not do this, ALWAYS check the `TES_MODE` configuration item in the config.yml file..


## Usage
[Please checkout our wiki](https://github.com/CyberPunkMetalHead/Binance-volatility-trading-bot/wiki/Setup-Guide)

## Troubleshooting

1. Read the [FAQ](FAQ.md)
2. Open an issue / check us out on `#troubleshooting` at [Discord](https://discord.gg/buD27Dmvu3) 🚀 
    - Do not spam, do not berate, we are all humans like you, this is an open source project, not a full time job. 

## 💥 Disclaimer

All investment strategies and investments involve risk of loss. 
**Nothing contained in this program, scripts, code or repositoy should be construed as investment advice.**
Any reference to an investment's past or potential performance is not, 
and should not be construed as, a recommendation or as a guarantee of 
any specific outcome or profit.
By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.
