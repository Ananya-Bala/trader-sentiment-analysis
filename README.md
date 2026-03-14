# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes how Bitcoin market sentiment (Fear/Greed Index) 
influences trader behavior and profitability on Hyperliquid.

The analysis evaluates trader performance across different sentiment regimes 
using metrics such as average PnL, win rate, trade frequency, and trader segmentation.

---

## Dataset Description

1. **Fear & Greed Index Dataset**
   - Date
   - Classification (Extreme Fear, Fear, Neutral, Greed, Extreme Greed)

2. **Historical Trader Data (Hyperliquid)**
   - Account
   - Execution Price
   - Size
   - Side
   - Closed PnL
   - Timestamp
   - Other trade-level attributes

---

## Analysis Overview

The notebook includes:

- Data cleaning and alignment
- Sentiment-based performance comparison
- Win rate analysis
- Trade participation analysis
- Trader segmentation (Frequent vs Infrequent)
- Key insights and actionable strategy recommendations

---

## Key Findings

- Profitability peaks during **Extreme Greed** periods.
- Win rates decline significantly during **Extreme Fear**.
- Moderate Fear outperforms Moderate Greed in win rate.
- Frequent traders experience amplified downside risk during negative sentiment.

---

## How to Run

1. Install Python 3.9+
2. Install required libraries:
pip install pandas numpy matplotlib seaborn

3. Open the notebook in Jupyter and run all cells.

---

## Repository Structure

- Trader Performance vs Market Sentiment Analysis.ipynb
- fear_greed_index.csv
- historical_data.csv.gz
- README.md
