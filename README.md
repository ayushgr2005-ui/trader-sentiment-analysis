# Trader Performance vs Market Sentiment Analysis

## 📌 Objective
Analyze how market sentiment (Fear/Greed) affects trader behavior and performance.

---

## 📊 Methodology
- Cleaned and processed sentiment + trading datasets
- Converted timestamps and aligned data by date
- Merged datasets to associate sentiment with each trade
- Created key metrics:
  - Daily PnL
  - Win rate
  - Trade frequency
  - Leverage & trade size
- Removed extreme outliers (1st–99th percentile)
- Performed analysis across sentiment categories
- Segmented traders based on frequency and performance
- Built a Random Forest model to predict profitability

---

## 🔍 Key Insights

### 1. Sentiment impacts performance
- Highest PnL and win rate during **Extreme Greed (~55%)**
- Lowest performance during **Extreme Fear (~29%)**

### 2. Risk-taking increases during Fear
- Larger trade sizes observed during Fear phases
- But profitability decreases → emotional trading behavior

### 3. Greed phases offer opportunity (with risk)
- Higher average PnL but also higher volatility

### 4. Trader segmentation matters
- Frequent traders perform better in Greed phases
- Infrequent traders perform better in Extreme Greed

---

## 🚀 Strategy Recommendations

### Strategy 1 — Reduce risk in Fear
Reduce leverage and position size during Fear/Extreme Fear

### Strategy 2 — Trade actively in Greed
Increase activity during Greed phases (with controlled risk)

### Strategy 3 — Avoid emotional trading
Avoid increasing trade size during Fear phases

---

## 🤖 Bonus — Predictive Model
- Built a Random Forest classifier to predict trade profitability
- Features used: leverage, trade size, trading frequency
- Feature importance shows leverage is a key driver

---

## 📁 Files
- `notebook.ipynb` → Full analysis
