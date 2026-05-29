# 📈 RELIANCE.NS Market Regime Analysis

A Data Science project focused on analyzing the historical behavior of **RELIANCE.NS** stock using market trends, trading volume, volatility, and regime classification techniques.

This project uses financial time-series analysis to identify different market conditions such as:

- Bullish Markets 📈
- Bearish Markets 📉
- Sideways/Neutral Markets ➖

The goal is to understand stock behavior through data-driven analysis and visualization.

---

# 🚀 Features

- Historical stock data analysis using Yahoo Finance
- Closing price trend analysis
- Trading volume analysis
- Market regime classification
- Volatility-based insights
- Time-series visualization
- Financial data preprocessing

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- yFinance
- Jupyter Notebook

---

# 📂 Project Structure

```bash
├── Untitled168.ipynb
├── README.md
├── RELIANCE.NS_closing_price_over_time.png
├── RELIANCE.NS_trading_volume_over_time.png
└── RELIANCE.NS_market_regime_distribution.png
📊 Closing Price Analysis

The graph below shows the historical closing price movement of RELIANCE.NS over time.




📌 Key Insights
RELIANCE has shown a strong long-term upward trend.
The stock experienced significant volatility during the 2020 market crash.
Post-2020 recovery displayed aggressive bullish momentum.
Trading activity spikes indicate periods of institutional participation and high market interest.
Sideways consolidation phases are visible before breakout movements.
🧠 Market Regime Classification

The project classifies market conditions into different regimes based on:

Price Momentum
Daily Returns
Volatility
Moving Average Trends
Trend Strength

Example logic:

if returns > threshold:
    regime = "Bullish"
elif returns < -threshold:
    regime = "Bearish"
else:
    regime = "Sideways"
📥 Dataset Source

Historical stock market data fetched directly from Yahoo Finance.

Ticker Used:

RELIANCE.NS
⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/reliance-market-regime-analysis.git

Move into the project directory:

cd reliance-market-regime-analysis

Install dependencies:

pip install -r requirements.txt

Run the notebook:

jupyter notebook
📦 Requirements
pandas
numpy
matplotlib
seaborn
yfinance
jupyter
🔥 Future Improvements
Hidden Markov Model (HMM) based regime detection
LSTM stock forecasting
Real-time market dashboard
Technical indicator integration
Portfolio optimization system
Risk prediction models
Automated trading signal generation
📈 Use Cases
Financial Data Analysis
Quantitative Finance
Stock Market Research
Algorithmic Trading
Risk Analytics
Investment Strategy Development
👨‍💻 Author
Ansh Kambli

Data Analyst | Aspiring Quantitative Analyst | AI Engineer

Skills
Financial Analytics
Machine Learning
Risk Modeling
Data Science
Predictive Analytics
