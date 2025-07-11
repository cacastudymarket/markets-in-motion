# markets-in-motion
Analyzing CPI &amp; FOMC effects on crypto and tech stocks
# 📊 Markets in Motion  
**Analyzing the Impact of CPI and FOMC News on Crypto and U.S. Tech Stocks**

---

## 📌 Overview

The crypto market and U.S. tech stocks are highly sensitive to macroeconomic announcements, particularly:
- 📈 CPI (Consumer Price Index)
- 🏦 FOMC (Federal Reserve’s interest rate decisions)

This project analyzes how CPI and FOMC releases impact price movement, daily return, and volatility across five key assets:
- Crypto: **BTC**, **ETH**
- U.S. Stocks: **AAPL**, **TSLA**, **NVDA**

---

## 🔧 Tools & Dataset

- **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
- **Data Sources**:  
  - Prices: `yfinance`, `CoinGecko API`  
  - Macro Events: `tradingeconomics.com`, `investing.com`
- **Timeframe**: Last 6–7 months
- **Granularity**: Daily prices ± 3 days around CPI/FOMC events

---

## 🧼 Data Preparation

- Collected crypto and stock daily prices
- Collected historical CPI and FOMC announcement dates
- Merged price data with event data
- Created new columns:
  - Daily return (`pct_change`)
  - Volatility (`rolling std`)
  - Moving Average (5-day)
  - Event tagging: CPI, FOMC

📁 [View Data Cleaning & Merging](./day1_collect_clean.ipynb)

---

## 📈 Exploratory Analysis

- Line chart of asset prices with CPI/FOMC markers
- Barplot of returns during macro events
- Volatility heatmap
- Pre-vs-post event correlation between crypto & stocks

📁 [View Exploratory Analysis](./day3_eda.ipynb)

---

## 📊 Comparative Insights

| Asset | Avg Return on CPI Day | Avg Return on FOMC Day |
|-------|------------------------|-------------------------|
| BTC   | +1.5%                  | +2.1%                   |
| ETH   | +1.2%                  | +1.9%                   |
| AAPL  | -0.3%                  | +0.6%                   |
| TSLA  | +0.5%                  | +1.3%                   |
| NVDA  | +0.4%                  | +1.0%                   |

- Return correlation between assets tends to increase after CPI/FOMC events.
- Breakouts above MA5 with large candles (>3% move) are more frequent in BTC and TSLA.

📁 [View Comparative Notebook](./day4_comparative.ipynb)

---

## 🧠 Market Behavior & Interpretation

- **Crypto assets** respond more aggressively to CPI reports, especially when inflation beats expectations.
- **Tech stocks** (especially AAPL) are more sensitive to FOMC guidance, reflecting institutional behavior.
- **Retail-driven assets** (like BTC and TSLA) exhibit stronger reactions—both fear and greed.
- Post-FOMC breakout patterns are more consistent and tradeable than CPI days.

📁 [Read Full Market Insight](./day5_insight.ipynb)

---

## ✅ Conclusion & Recommendations

> 🧭 CPI days often spark emotional volatility. Consider **avoid trading** before CPI, especially in crypto.  
> 🧭 FOMC provides **clearer direction**—ideal for breakout strategies using MA/candlestick confirmation.  
> 🧭 Increased correlation between assets shows macro news drives cross-market sentiment, especially during uncertainty.

---

## 👩‍💻 About Me

I'm a beginner data analyst and retail trader exploring how **macroeconomic fundamentals** intersect with **price behavior**.  
This project represents my first attempt at applying Python-based data analysis to real financial market data.

---

## 📎 Project Files

| File | Description |
|------|-------------|
| `merged_data.csv` | Final merged dataset (prices + event tags) |
| `day1_collect_clean.ipynb` | Data collection and preprocessing |
| `day3_eda.ipynb` | Exploratory data visualization |
| `day4_comparative.ipynb` | Comparative asset behavior |
| `day5_insight.ipynb` | Interpretations & market insights |
