# Data Science Assignment – Trader Behavior Insights

**Candidate:** Bhumika Tusamad

---

## Overview
This repository contains my submission for the **Web3 Trading Data Science Internship**.  
The goal of this analysis was to explore how **trader behavior** interacts with **Bitcoin market sentiment** (Fear vs Greed) and uncover patterns that could inform smarter trading strategies.

The analysis focuses on understanding:
- Trader **profitability** relative to market sentiment
- Differences in **trade sizes** across different sentiment periods
- Buy/Sell behavior of traders in relation to Fear and Greed
- Patterns that can inform trading decisions

---

## Datasets Used

1. **Trader Data (`trader_data.csv`)**  
   - Historical trades from Hyperliquid including trade size, execution price, trade direction, and closed PnL.

2. **Market Sentiment (`bitcoin_sentiment.csv`)**  
   - Bitcoin Fear & Greed Index for each day, showing overall market sentiment.

## How to Use

1. Open `notebook_1.ipynb` in **Google Colab**.
2. Mount Google Drive if needed to access the CSV files.
3. Run all cells sequentially to reproduce the analysis and visualizations.
4. All charts and the report are saved in the `outputs/` folder.

---

## Key Insights

- Traders are generally **most profitable during Greed** periods.
- **Trade sizes** are larger during Greed and smaller during Extreme Fear, showing cautious behavior during extreme market conditions.
- **Buy trades** dominate during Fear periods, reflecting attempts to “buy the dip.”
- **Sell trades** dominate during Extreme Greed periods, reflecting profit-taking behavior.
- Overall, trader behavior **partially aligns with market sentiment**, offering actionable insights for smarter trading strategies.

---

## Notes

- Analysis conducted using **Python 3.12**, **pandas**, **matplotlib**, and **seaborn**.
- This repository is structured for **clarity, reproducibility, and ease of interpretation**.


## Folder Structure

