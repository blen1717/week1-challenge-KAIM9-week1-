# Week 1 Challenge: Predicting Price Moves with News Sentiment

## 📌 Overview
This project analyzes the relationship between financial news sentiment and stock price movements for 4 major tech stocks: AAPL, AMZN, META, NVDA.

## 📊 Tasks Completed

### Task 1: Exploratory Data Analysis (EDA)
- Analyzed 13,646 news articles
- Top publishers identified
- Time series analysis of publication trends
- Keyword extraction from headlines

### Task 2: Technical Indicators
Calculated for all 4 stocks:
- SMA (20-day & 50-day)
- RSI (14-day)
- MACD

### Task 3: Sentiment Analysis & Correlation
- Used TextBlob for sentiment scoring
- Merged sentiment with daily returns (61 matching days)
- Correlation coefficient: 0.1581
- P-value: 0.2235 (not statistically significant)

## 📈 Key Findings
- Weak positive correlation between sentiment and returns (r=0.1581)
- Positive sentiment days showed +0.25% average return
- Neutral sentiment days showed -0.25% average return
- Negative sentiment days showed 0.00% average return
- AMZN, META, NVDA had insufficient matching data

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- TextBlob (NLP)
- Matplotlib, Seaborn
- Scikit-learn

## 📁 Repository Structure
## 🚀 How to Run
1. Clone this repository
2. Install dependencies: pip install -r requirements.txt
3. Open the Jupyter notebook
4. Run all cells

## 👩‍💻 Author
Blen Assefa

## 📅 Date
May 2026
