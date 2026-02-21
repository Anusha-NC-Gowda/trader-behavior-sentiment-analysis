# trader-behavior-sentiment-analysis
Analysis of trader performance vs Bitcoin Fear/Greed sentiment
# Trader Performance vs Market Sentiment Analysis

## Objective
This project analyzes how Bitcoin Fear & Greed Index sentiment influences trader behavior and performance. The goal is to identify behavioral patterns and derive actionable strategy recommendations.

---

## Methodology

1. **Data Preparation**
   - Loaded Fear & Greed Index dataset and Historical Trader dataset.
   - Converted timestamps into daily date format.
   - Merged datasets using date alignment.

2. **Feature Engineering**
   - Calculated Average Closed PnL per sentiment regime.
   - Computed Win Rate (percentage of profitable trades).
   - Measured Trade Frequency.
   - Analyzed Average Position Size (USD).

3. **Comparative Analysis**
   - Compared trader performance across:
     - Extreme Fear
     - Fear
     - Neutral
     - Greed
     - Extreme Greed

---

## Key Insights

- Extreme Greed shows highest average profitability.
- Extreme Fear increases trade frequency but reduces win rate.
- Traders take larger position sizes during Fear conditions.
- High activity does not always mean high profitability.

---

## Strategy Recommendations

- Reduce position size during Extreme Fear.
- Use controlled trend-following during Extreme Greed.
- Avoid overtrading in volatile conditions.

---

## Tools Used
Python, Pandas, Matplotlib
