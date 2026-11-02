# Simple Trend & Momentum Buy/Sell Indicator (TradingView Pine Script v6)

A clean, non-repainting trend and momentum indicator developed in Pine Script v6 for TradingView. It pairs a dual Exponential Moving Average (9 & 21 EMA) cross with an RSI 50-line momentum gatekeeper to eliminate consolidation false breakouts.

---

## 📺 Video Walkthrough
Watch the complete step-by-step setup and chart breakdown:
[![Watch Video](https://img.shields.io/badge/YouTube-Watch%20Tutorial-red?logo=youtube)](https://youtu.be/BBGP5E9EM-0)

---

## 🚀 Strategy Logic

1. **Trend Engine:** 9 EMA (Fast) vs. 21 EMA (Slow baseline).
2. **Momentum Filter:** RSI (14) must confirm the breakout direction:
   - **🟢 BUY:** 9 EMA crosses above 21 EMA **AND** RSI > 50.
   - **🔴 SELL:** 9 EMA crosses below 21 EMA **AND** RSI < 50.
3. **No Repaint:** Signals evaluate and alert strictly at candle close (`barstate.isconfirmed`).

---

## 🛠 How to Use on TradingView (100% Free)

1. Open any chart on [TradingView](https://www.tradingview.com/).
2. Click the **Pine Editor** tab at the bottom toolbar.
3. Open `indicator.pine` from this repository, copy the raw code, and paste it into the editor.
4. Click **Save**, then click **Add to chart**.

---

## 🌐 Connect & Community

- **Website:** [apollofinancialservices.in](https://apollofinancialservices.in)
- **Telegram Channel:** [@apollofinancialservices](https://t.me/apollofinancialservices)
- **Direct Telegram:** [@DV122](https://t.me/DV122)
- **YouTube:** [@apollofinancialservices](https://www.youtube.com/@apollofinancialservices)
- **Medium:** [@dhavalvisariya](https://medium.com/@dhavalvisariya)
- **Email:** info.apollofinancialservices@gmail.com
