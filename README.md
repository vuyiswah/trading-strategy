# Pro Multi-Confluence Strategy v2.0 (PMCS)

A professional-grade TradingView strategy built in Pine Script v6.

## Features

- Multi-confluence entry logic (EMA stack, VWAP, RSI, MACD, ADX, BOS, S/R, Volume, HTF)
- ATR-based dynamic Stop Loss & Take Profit
- Partial TP, Break-Even, and Trailing Stop
- Daily loss circuit breaker & consecutive loss filter
- Live dashboard (Win Rate, Profit Factor, Net Profit, Trend, Position)
- Webhook-compatible alerts
- Works on Forex, Crypto, Indices, Stocks — 5m to Daily

## How to Use

1. Open TradingView → any chart
2. Click **Pine Editor** at the bottom
3. Paste the contents of `PMCS_v2.pine`
4. Click **Add to chart**
5. Open **Strategy Tester** tab to backtest

## Recommended Settings

| Market | Timeframe | EMA Stack |
|--------|-----------|-----------|
| Forex majors | 1H / 4H | 21 / 50 / 200 |
| Crypto BTC/ETH | 4H / Daily | 21 / 50 / 200 |
| US Indices | 15m / 1H | 21 / 50 / 200 |

## Risk Warning

Past performance does not guarantee future results. Always test on a demo account before live trading.
