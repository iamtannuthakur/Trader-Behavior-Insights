# Trader-Behavior-Insights

Insight Report: Analysis of Trader Behavior Based on Market Sentiment (Fear & Greed)
👩‍💻 Objective:
To explore the relationship between trader performance and Bitcoin market sentiment (Fear/Greed), uncover hidden patterns, and derive insights that support smarter trading strategies.

📊 Dataset Overview:
Sentiment Dataset:

Columns: date_only, classification (values: Fear or Greed)

Source: Fear & Greed Index

Trader Activity Dataset (Hyperliquid):

Columns: Account, Size USD, Closed PnL, Side, Timestamp, etc.

Both datasets were merged using the date_only column.

🔍 Key Insights:

1️⃣ Trading Volume Distribution:
The number of trades was fairly balanced between Fear and Greed days.

However, Greed days saw slightly higher volume per trade, indicating higher risk appetite.

2️⃣ Win Rate by Sentiment:
Fear days showed a higher average win rate.

This suggests that traders tend to be more careful and calculated during fearful market conditions.

3️⃣ Profit/Loss Trends:
On average, Greed days had higher profits, but also heavier losses.

Fear days showed more consistent PnL with fewer extreme spikes.

Recommendation: Risk management is critical on Greed days.

4️⃣ Top 10 Traders by Profit on Greed Days:
A small group of traders earned significant profits on Greed days.

These traders appear to follow momentum or aggressive strategies.

5️⃣ Top 15 Most Active Traders (by Number of Trades):
Several accounts are consistently active, executing a high number of trades.

This suggests the use of automated or high-frequency strategies.

6️⃣ Buy vs Sell Activity by Sentiment:
Buy trades increase during Greed days, showing trader optimism.

Fear days see a slight rise in Sell activity, reflecting cautious, risk-off behavior.
