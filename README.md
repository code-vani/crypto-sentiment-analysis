
# Crypto Sentiment Analysis

This project investigates how **Bitcoin market sentiment** (Fear & Greed Index) influences real trading behavior using **Hyperliquid historical trader data**.

The goal is to uncover if trader decisions (PnL, leverage, volume, risk) align with market emotions and to identify signals that can enhance strategy performance.

---

## 📂 Project Structure (Submission Format Approved ✅)

```

ds_vanshika_garg/
├── notebook1.ipynb                 # Primary Google Colab work
├── csv_files/                      # Processed + analysis datasets
│   └── *.csv
├── outputs/                        # Charts, graphs, visual insights
│   └── *.png / *.jpg
├── ds_report.pdf                   # Final analysis report
└── README.md                       # Documentation (this file)

```

> ✅ The exact same structure is maintained in Google Drive and GitHub.

---

## 📥 Datasets

If datasets are missing in the repo, download them from here:

- **Historical Trader Data (Hyperliquid):**  
  https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing

- **Fear & Greed Sentiment Data:**  
  https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing

Place both files in a folder in Google Drive, for example:

```

/MyDrive/Trader_Analysis

````

---

## ⚙️ Setup Instructions (Google Colab)

1️⃣ Mount Google Drive in notebook  
```python
from google.colab import drive
drive.mount('/content/drive')
````

2️⃣ Import required libraries
(Already included inside the notebook)

3️⃣ Load datasets using correct file paths

```python
import pandas as pd
sentiment = pd.read_csv('/content/drive/MyDrive/Trader_Analysis/fear_greed.csv')
trades = pd.read_csv('/content/drive/MyDrive/Trader_Analysis/hyperliquid_trades.csv')
```

> ✅ Ensure folder structure & file paths match

---

## 📊 Project Workflow

✔ Data cleaning & preprocessing
✔ Mapping of sentiment → Fear / Greed
✔ Feature engineering (PnL, leverage, volume)
✔ Market-timing analytics
✔ ML-based trade outcome prediction
✔ ANOVA statistical significance testing
✔ Sharpe Ratio & risk evaluation
✔ Visual EDA for decision insights

---

## 🔍 Key Findings Summary

📌 Traders show **higher leverage but lower Sharpe** during *Greed*
📌 Fear periods lead to *more controlled* risk taking
📌 Market sentiment can improve **entry timing accuracy**
📌 Sentiment-aware strategies outperform baseline signals

> These insights form the foundation for **behavior-aware trading systems** ✅

---

## 📌 Google Colab Notebook

Accessible to anyone with the link (view-only):

> https://drive.google.com/drive/folders/10cnjs2znPlSWsc23s9NysmsadC5Ko5we?usp=sharing

---

## ✅ Objective

Deliver actionable insights to help Web3 trading teams:

✅ Manage risk efficiently
✅ Time trades better using market mood
✅ Improve profitability metrics

---

## 🧑‍💻 Author

**Vanshika Garg**
Data Science Candidate – Web3 Trading Team
GitHub: *(optional to add)*




Just tell me — I’d be happy to help! 🚀
```
