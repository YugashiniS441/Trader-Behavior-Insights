# Trader-Behavior-Insights
# Trader Behaviour Analysis based on Market Sentiment

## 📌 Overview
This project analyzes trader performance across different sentiment regimes — such as **Fear, Greed, and Extreme conditions** — to uncover patterns in decision-making and identify traders who consistently respond well to market shifts.  
By combining market sentiment indicators with performance metrics like **PnL, Win Rate, Sharpe Ratio, Profit Factor, and Maximum Drawdown**, we aim to deliver actionable insights for smarter trading strategies.

---

## 🎯 Objectives
- Analyze trader performance in different **market sentiment conditions**.
- Detect traders showing **contrarian strength** during adverse market regimes.
- Correlate **sentiment indicators** with key trading metrics.
- Provide a **data-driven framework** for performance optimization.

---

## 🗂 Dataset
The dataset includes:
- **trade_date** – Date of the trade.
- **PnL** – Profit and Loss.
- **Win Rate** – Ratio of profitable trades to total trades.
- **Sharpe Ratio** – Risk-adjusted return metric.
- **Profit Factor** – Ratio of gross profit to gross loss.
- **Maximum Drawdown** – Largest drop from peak equity.
- **Market Sentiment** – Categorical variable representing Fear, Greed, or Extreme market regimes.

---

## ⚙️ Methodology
1. **Data Cleaning**  
   - Convert `trade_date` to datetime format.  
   - Handle missing values and remove inconsistencies.

2. **Sentiment Regime Segmentation**  
   - Categorize trades into sentiment buckets (Fear, Greed, Extreme).
   
3. **Performance Analysis**  
   - Compare trader metrics across regimes.
   - Identify consistently profitable traders.

4. **Correlation Analysis**  
   - Explore relationships between sentiment indicators and trader outcomes.

5. **Visualization**  
   - Generate plots for performance trends, sentiment distributions, and correlations.

---

## 📊 Key Metrics
- **PnL (Profit & Loss)** – Measures profitability.
- **Win Rate (%)** – Success ratio of trades.
- **Sharpe Ratio** – Adjusted return per unit of risk.
- **Profit Factor** – Indicates robustness of trading.
- **Max Drawdown** – Measures risk exposure.

---

## 🖥️ Technologies Used
- **Python** – Data processing & analysis.
- **Pandas** – Data manipulation.
- **Matplotlib / Seaborn** – Visualization.
- **Jupyter Notebook** – Interactive analysis.

---

## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/username/trader-behaviour-analysis.git

# Navigate to folder
cd trader-behaviour-analysis

# Install requirements
pip install -r requirements.txt

# Open notebook
jupyter notebook trader_behaviour.ipynb
