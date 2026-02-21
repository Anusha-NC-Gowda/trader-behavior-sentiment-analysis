# Trader Performance vs Market Sentiment Analysis

Author: Anusha N C Gowda  
Role: AIML Student | Data Analytics Enthusiast  

---

## Objective
This project analyzes how Bitcoin Fear & Greed Index sentiment influences trader behavior and performance. The goal is to identify behavioral patterns and derive actionable strategy recommendations.

---

## Methodology

### 1. Data Preparation
- Loaded Fear & Greed Index dataset and Historical Trader dataset.
- Converted timestamps into daily date format.
- Merged datasets using date alignment.

### 2. Feature Engineering
- Calculated Average Closed PnL per sentiment regime.
- Computed Win Rate (percentage of profitable trades).
- Measured Trade Frequency.
- Analyzed Average Position Size (USD).

### 3. Comparative Analysis
Compared trader performance across:
- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

---

## Key Insights

- Extreme Greed shows the highest average profitability.
- Extreme Fear increases trade frequency but reduces win rate.
- Traders take larger position sizes during Fear conditions.
- Higher activity does not always lead to higher profitability.

---

## Strategy Recommendations

- Reduce position size during Extreme Fear.
- Use controlled trend-following strategies during Extreme Greed.
- Avoid overtrading in volatile market conditions.

---

## Business Impact

This analysis demonstrates how trader behavior shifts under different sentiment regimes.  
By identifying profitability patterns and risk-taking tendencies, trading systems can:

- Dynamically adjust position sizing
- Implement volatility-based risk controls
- Reduce panic-driven losses during extreme fear
- Improve risk-adjusted returns during bullish momentum

---

## Tools Used
Python, Pandas, Matplotlib
