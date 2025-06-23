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

1️⃣ Trading Volume Distribution (Fear vs Greed):
The number of trades was fairly balanced between Fear and Greed days.

However, Greed days saw slightly higher volume per trade, indicating higher risk appetite.

2️⃣ Win Rate by Sentiment:
Fear days showed a higher average win rate.

This suggests that traders tend to be more careful and calculated during fearful market conditions.

3️⃣ Profit/Loss Trends:
On average, Greed days had higher profits, but also heavier losses.

Fear days showed more consistent PnL with fewer extreme spikes.

Recommendation: Risk management is critical on Greed days.

4️⃣ Top Trader Behavior:
Some accounts consistently performed better during Greed days, showing strong momentum trading.

These top traders had higher leverage usage and bigger position sizes.

5️⃣ Size USD vs PnL Scatter Plot:
A noticeable trend: larger trades resulted in wider PnL swings, especially on Greed days.

Smaller trades remained more stable during Fear periods.

6️⃣ Daily PnL Trends:
Using date-wise aggregation, we observed that:

Profitable streaks often align with Fear days.

Loss streaks are often triggered after consecutive Greed days.
