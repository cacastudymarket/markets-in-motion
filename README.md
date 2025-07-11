# 📊 Markets in Motion  
**Analyzing the Impact of CPI and FOMC News on Crypto and U.S. Tech Stocks**

---

## 📌 Overview

Crypto assets and U.S. tech stocks are highly sensitive to macroeconomic announcements — especially:
- 📈 CPI (Consumer Price Index)
- 🏦 FOMC (Federal Reserve interest rate decisions)

This project explores how these economic events affect market behavior across:
- **Cryptocurrencies**: BTC (Bitcoin), ETH (Ethereum)
- **U.S. Tech Stocks**: AAPL (Apple), TSLA (Tesla), NVDA (Nvidia)

We analyze:
- Daily return & volatility ±3 days before/after macro events
- Price reactions and correlation shifts
- Institutional vs retail-driven response patterns

---

## 🛠️ Tools & Technologies

- Python, Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `yfinance`, `plotly`
- Data Sources:
  - Historical prices: CoinGecko API, Yahoo Finance (`yfinance`)
  - Macro events: `tradingeconomics.com`, manually compiled

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `btc_data.csv` | Bitcoin historical price data |
| `eth_data.csv` | Ethereum historical price data |
| `tech_stock_data.csv` | Tech stock prices (AAPL, TSLA, NVDA) |
| `event_dates.csv` | Cleaned macro event dates (CPI & FOMC) |
| `merged_data.csv` | Final dataset used for analysis |
| `day1_data_collection.ipynb` | Data scraping & collection |
| `day2_preprocessing.ipynb` | Merging datasets, labeling events, adding returns & volatility |
| `day3_eda.ipynb` | Exploratory data analysis & visualization |
| `day4_comperative_analysis.ipynb` | Comparative analysis of asset reactions |

---

## 📊 Key Analysis

### 🔹 Market Behavior Around Events
- BTC and ETH showed stronger volatility spikes around CPI release dates, especially when inflation data was unexpected.
- Tech stocks (AAPL, TSLA, NVDA) were more sensitive to FOMC decisions, showing delayed but clearer directional movement.

### 🔹 Correlation Shift
- Asset correlations increased after CPI/FOMC events — indicating synchronized market behavior during uncertainty.

### 🔹 Return & Volatility Summary (Example)

| Asset | Avg Return (CPI Day) | Avg Return (FOMC Day) |
|-------|----------------------|------------------------|
| BTC   | +1.4%                | +2.0%                  |
| ETH   | +1.1%                | +1.8%                  |
| AAPL  | -0.2%                | +0.5%                  |
| TSLA  | +0.3%                | +1.2%                  |
| NVDA  | +0.4%                | +1.0%                  |

---

## 🧠 Key Insights

- Crypto reacts faster and more emotionally to CPI news (retail-driven).
- Tech stocks respond more cleanly to FOMC decisions, possibly due to institutional dominance.
- Volatility is opportunity — post-event breakout patterns are useful for short-term traders.

---

## 📝 Notebooks

- 📄 [Day 1 – Data Collection](./day1_data_collection.ipynb)
- 📄 [Day 2 – Preprocessing](./day2_preprocessing.ipynb)
- 📄 [Day 3 – EDA & Visualizations](./day3_eda.ipynb)
- 📄 [Day 4 – Comparative Analysis](./day4_comperative_analysis.ipynb)

---

## 👩‍💻 About Me

I’m an aspiring data analyst and trader, exploring how macroeconomic events shape market dynamics.  
This project represents my journey combining technical analysis, fundamentals, and Python-based data processing.

---

## 📬 Contact / Portfolio

> Feel free to connect or view more projects via my GitHub profile.

---

