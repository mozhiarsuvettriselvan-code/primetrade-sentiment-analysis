# Primetrade Sentiment Analysis
Trader Performance vs Market Sentiment  
Primetrade.ai – Data Science Internship Assignment  

---

## Executive Summary

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance on Hyperliquid.

The objective was to determine whether sentiment regimes influence profitability, trader behavior, and risk exposure — and whether these signals can inform smarter trading strategies.

---

## Key Performance Insights

### 1️⃣ Profitability Varies by Sentiment Regime
- Average trade profitability is highest during **Extreme Greed** periods.
- Neutral and Extreme Fear regimes exhibit significantly lower returns.
  
This indicates traders perform better in strongly bullish environments.

### 2️⃣ Win Rates Improve in Bullish Conditions
- Win rates peak during Extreme Greed (~46%).
- Win rates decline sharply during Extreme Fear (~37%).

Trader success is strongly influenced by market sentiment conditions.

---

## Behavioral Insights

### 3️⃣ Trade Frequency Spikes During Fear
- Trading activity increases dramatically during Extreme Fear (~1,500+ trades/day).
- This is 4–5x higher than Greed periods.
- However, higher activity does **not** translate into higher profitability.

This suggests potential overtrading and emotionally driven behavior during volatile markets.

---

### 4️⃣ Position Sizing Increases During Uncertainty
- Average position size is highest during Fear regimes (~$7,800).
- Extreme Greed shows smaller average positions but higher profitability.

This implies traders increase risk exposure during uncertainty, potentially driven by behavioral biases such as dip-buying tendencies.

---

### 5️⃣ Activity-Based Segmentation Reveals Overtrading Risk
- Low-activity traders consistently outperform high-activity traders.
- The gap is especially large during Greed and Extreme Greed periods.

Selective participation appears more profitable than frequent trading.

---

## Predictive Modeling (Bonus Analysis)

A Random Forest classifier was trained to predict trade profitability using:

- Market sentiment classification  
- Position size (USD)  
- Trader activity segment  

Using an 80/20 train-test split, the model achieved **61% accuracy** on unseen data.

Feature importance analysis indicates:
- Position size is the dominant predictor.
- Sentiment and behavioral variables provide additional predictive signal.

This suggests sentiment-aware trading frameworks may offer measurable predictive advantage.

---

## Strategic Implications

Based on the findings:

- Reduce leverage and trade frequency during Fear regimes.
- Discourage overtrading through disciplined participation.
- Implement sentiment-aware risk management controls.
- Encourage selective engagement over high-frequency trading.

---

