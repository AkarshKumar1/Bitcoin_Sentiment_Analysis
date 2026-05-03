# 📊 Bitcoin Sentiment vs Trader Performance Analysis

This project analyzes the relationship between **Bitcoin market sentiment** (Fear / Greed Index) and **trader performance** using historical trading data.

The goal of this project is to understand how market emotions influence trading behavior, profitability, and decision-making.

---

# 🚀 Project Objective

To explore whether Bitcoin market sentiment affects:

- Trader profitability (PnL)
- Trading frequency
- Buy/Sell behavior
- Risk-taking patterns
- Performance during Fear vs Greed market conditions

---

# 📂 Dataset Used

## 1️⃣ Historical Trader Data

Contains:

- Account ID
- Coin / Symbol
- Execution Price
- Trade Size
- Side (Buy / Sell)
- Closed PnL
- Fee
- Timestamp

## 2️⃣ Fear & Greed Index Data

Contains:

- Timestamp
- Sentiment Value
- Classification:
  - Extreme Fear
  - Fear
  - Neutral
  - Greed
  - Extreme Greed

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📁 Project Structure

```bash
Bitcoin-Sentiment-Analysis/
│── datasets/
│   ├── historical_data.csv
│   └── fear_greed_index.csv
│
│── bitcoin_sentiment_analysis.ipynb
│── report.pdf
│── README.md
```

# ⚙️ Steps Performed

## 1️⃣ Data Cleaning

- Converted timestamps into readable date format
- Removed missing values
- Standardized column names
- Converted numeric columns properly

## 2️⃣ Data Merging

- Merged both datasets using common date column.

## 3️⃣ Exploratory Data Analysis

Performed analysis on:

- Average PnL by sentiment
- Total PnL by sentiment
- Trade count by sentiment
- Buy vs Sell behavior
- Top trader performance

## 4️⃣ Data Visualization

Created charts such as:

- Bar chart for Average PnL
- Trade Frequency chart
- Profitability comparison

# 📊 Key Insights

- Traders achieved highest profits during Greed phases.
- Profitability reduced during Extreme Greed, likely due to overconfidence.
- Fear phases showed moderate profitability.
- Market sentiment has a clear impact on trading behavior.
- Stable sentiment conditions performed better than emotional extremes.

# 💡 Conclusion

This project shows that market sentiment plays an important role in trader decision-making and profitability.

Understanding Fear & Greed cycles can help traders avoid emotional mistakes and make smarter trading decisions.

# ▶️ How to Run

## Install Required Libraries

```text
pip install pandas numpy matplotlib seaborn jupyter
```
## Run Notebook

```text
jupyter notebook
```
Then open:

```text
Bitcoin_Sentiment_Analysis.ipynb
```

# 📌 Future Improvements

- Apply Machine Learning models for prediction
- Add live crypto market data
- Build dashboard using Streamlit / Power BI
- Sentiment forecasting

# 👤 Author

Akarsh Kumar
