# Trader Behavior Analysis Based on Market Sentiment

## Overview
This project analyzes the relationship between trader behavior and Bitcoin market sentiment using historical trade data from Hyperliquid and the Bitcoin Fear & Greed Index.  
The goal is to understand how market sentiment (Fear vs Greed) influences trading activity, risk-taking, and performance.

---

## Datasets
1. **Bitcoin Market Sentiment Dataset**
   - Fields: Date, Classification (Fear / Greed)

2. **Historical Trader Data (Hyperliquid)**
   - Fields include trade size (USD), PnL, timestamps, direction, and execution details

Both datasets were aligned at a daily level for analysis.

---

## Methodology
- Converted trade timestamps (UNIX milliseconds) to daily dates
- Standardized sentiment data to daily granularity
- Merged datasets on date
- Used trade size (USD) and PnL as proxies for risk and performance
- Conducted exploratory data analysis to identify behavioral patterns

---

## Key Insights
- Trading activity increases during Greed phases and declines during Fear phases
- Larger trade sizes are observed during Greed, indicating higher risk appetite
- PnL volatility is higher during Greed periods
- Increased risk-taking during Greed does not significantly improve win rates

---

## Project Structure
