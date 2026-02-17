📊 Trade Sentiment vs Trader Performance Analysis
📌 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on Hyperliquid.

The goal is to determine whether market sentiment regimes influence:

Profitability

Win rate

Trading activity

Directional behavior (Bullish vs Bearish bias)

🎯 Objectives

This analysis answers the following:

Does trader performance differ between Fear and Greed days?

Do traders change behavior based on sentiment?

Can insights be converted into actionable trading strategies?

📂 Datasets
1️⃣ Bitcoin Fear & Greed Index

Daily sentiment classification

Sentiment value (0–100)

Categories:

Extreme Fear

Fear

Neutral

Greed

Extreme Greed

Date range: 2018–2025

2️⃣ Hyperliquid Historical Trader Data

211,224 trade-level records

Includes:

Closed PnL

Fees

Direction

Timestamp

Date range: 2023–2025

🛠️ Data Preparation

Verified no missing values or duplicates

Converted timestamps to datetime format

Normalized data to daily frequency

Identified overlapping date range:

2023-05-01 → 2025-05-01

Created daily performance metrics:

Total PnL

Total Fees

Net PnL

Win Rate (%)

Number of Trades

Bullish vs Bearish trade counts

Final merged dataset:

479 trading days

📊 Analysis & Key Findings
🔹 1. Profitability Differs by Sentiment

Highest average Net PnL observed during Extreme Fear

Lower profitability during Greed regimes

Win rate highest during Extreme Greed, but profits lower

Insight:
Fear-driven volatility creates stronger profit opportunities.

🔹 2. Behavioral Shift by Sentiment

Traders buy aggressively during Fear

Traders short more during Greed

Bull/Bear ratio confirms contrarian positioning

Insight:
Traders tend to buy panic and short optimism.

🔹 3. Volatility Drives Performance

Correlation findings:

Trade activity vs Net PnL: 0.35

Sentiment value vs Trade activity: -0.24

Insight:
Higher volatility regimes increase trading activity and profitability.

📈 Visualizations Included

Average Net PnL by Sentiment

Average Win Rate by Sentiment

Trade Frequency by Sentiment

Bull vs Bear Bias Chart

Correlation Heatmap

💡 Strategy Recommendations

Based on findings:

Increase exposure during Fear regimes

Reduce leverage during Extreme Greed

Apply volatility-adaptive position sizing

🧰 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🚀 Conclusion

Trader profitability and behavior are significantly influenced by sentiment regimes.

Fear environments generate higher volatility and stronger profit opportunities, while Greed regimes show reduced profitability and stronger bearish positioning.

This supports the development of sentiment-aware trading strategies.
