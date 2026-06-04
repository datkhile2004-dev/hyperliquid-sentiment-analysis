# 🚀 Hyperliquid Trader Behavior Analysis Using Bitcoin Market Sentiment

## 📌 Project Overview

This project analyzes how **Bitcoin market sentiment (Fear/Greed Index)** influences **trader behavior and performance on Hyperliquid**. The objective is to uncover behavioral patterns in trading activity and identify actionable insights that could inform smarter trading strategies.

---

## 🎯 Objective

The main objective of this project is to analyze the relationship between **market sentiment** and **trader performance** by answering the following questions:

✅ Does trader performance differ during **Fear vs Greed** market conditions?
✅ Do traders change behavior based on sentiment?
✅ How do different trader segments behave?
✅ Can actionable trading strategies be derived from these insights?

---

## 📂 Dataset Information

### 📈 1. Bitcoin Market Sentiment Dataset

Contains daily market sentiment classifications:

* 😨 Fear
* 😌 Neutral
* 🤑 Greed
* 🚀 Extreme Greed

**Columns Used:**

* `date`
* `classification`

---

### 💹 2. Historical Trader Data (Hyperliquid)

Contains historical trader activity including:

**Columns Used:**

* `Account`
* `Coin`
* `Execution Price`
* `Size USD`
* `Side`
* `Timestamp`
* `Closed PnL`
* `Direction`

---

## 🛠️ Tech Stack

* 🐍 **Python**
* 🐼 **Pandas**
* 🔢 **NumPy**
* 📊 **Matplotlib**
* 📉 **Seaborn**
* 🤖 **Scikit-learn**
* 📓 **Jupyter Notebook**

---

## ⚙️ Project Workflow

### 🧹 Part A — Data Preparation

The following preprocessing steps were performed:

✅ Loaded and inspected datasets
✅ Checked missing values and duplicates
✅ Converted timestamps into datetime format
✅ Aligned both datasets at **daily level**
✅ Merged sentiment data with trading data

### 📏 Key Metrics Created

* 💰 Daily PnL per trader
* 🎯 Win rate
* 💵 Average trade size
* 📅 Trade frequency
* 📊 Long vs Short ratio
* ⚠️ Risk exposure proxy using trade size (Size USD)

> **Note:** Since leverage information was unavailable in the dataset, **trade size (USD)** was used as a proxy for trading exposure/risk.

---

## 📊 Part B — Analysis

### 💸 Performance Analysis

The following performance indicators were analyzed across sentiment conditions:

* Average PnL
* Win rate
* Drawdown proxy

### 🧠 Trader Behavior Analysis

Behavioral differences were analyzed using:

* 📈 Trade frequency
* 💰 Position size
* 🔄 Long/Short bias
* 📉 Trading activity across sentiment periods

### 👥 Trader Segmentation

#### 🔥 High Risk vs Low Risk Traders

Segmented using average **trade size (USD)**.

#### ⚡ Frequent vs Infrequent Traders

Segmented using total trading activity.

#### 🏆 Consistent Winners vs Inconsistent Traders

Segmented using trader **win rate**.

---

## 🔍 Key Insights

### 📌 Insight 1: Market Sentiment Influences Trading Performance

Trader profitability and win rates varied across different sentiment conditions, suggesting market psychology impacts trading outcomes.

### 📌 Insight 2: Trader Behavior Changes During Fear and Greed Markets

Fear periods showed higher trading activity, while position sizing and market participation shifted depending on sentiment.

### 📌 Insight 3: Active and Consistent Traders Perform Better

Frequent traders and consistent winners generally demonstrated stronger profitability compared to less active and inconsistent traders.

---

## 💡 Actionable Trading Strategies

### 🛡️ Strategy 1: Reduce Risk During Fear Markets

Inconsistent traders should reduce position size during Fear periods to manage downside risk and avoid emotional trading.

### 🚀 Strategy 2: Increase Participation During Greed Markets

Frequent traders may benefit from increased market participation during Greed periods while maintaining disciplined risk management.

---

## 🎁 Bonus Analysis

### 🤖 Trader Clustering (Behavioral Archetypes)

A clustering approach was implemented using **KMeans** to identify trader archetypes based on:

* 📈 Average PnL
* 💵 Trade Size
* 🎯 Win Rate

Trader groups included:

* 🟢 Conservative Traders
* 🔴 Aggressive Traders
* 🔵 Balanced Traders


---

## ▶️ How to Run the Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/hyperliquid-sentiment-analysis.git
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
hyperliquid_sentiment_analysis.ipynb
```

---

## 📚 Dataset Source

The datasets used in this project were provided as part of an assignment involving:

📌 Bitcoin Fear & Greed sentiment data
📌 Hyperliquid historical trader activity

Due to file size limitations, raw datasets are not included in this repository.

---

## 🔮 Future Improvements

✅ Predictive modeling for trader profitability
✅ Streamlit dashboard for interactive exploration
✅ Advanced trader behavioral clustering
✅ Market volatility prediction

---

## 👩‍💻 Author

**Payal Datkhile**
🎓 IT Student | Aspiring Data Analyst
📊 Passionate about Data Analytics, Python, Machine Learning, and Visualization
