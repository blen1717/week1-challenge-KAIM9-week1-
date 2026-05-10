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
- Merged sentiment with daily returns
- Correlation coefficient: 0.1581
- P-value: 0.2235 (not statistically significant)

## 📈 Key Findings
- Weak positive correlation between sentiment and returns (r=0.1581)
- Positive sentiment days showed +0.25% average return
- Neutral sentiment days showed -0.25% average return
- AMZN, META, NVDA had insufficient matching data

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- TextBlob (NLP)
- Matplotlib, Seaborn
## 🔬 Advanced NLP Analysis (Planned)

### Topic Modeling with LDA
To identify common themes in financial news headlines, I will implement Latent Dirichlet Allocation (LDA). Expected topics include:

| Topic | Keywords |
|-------|----------|
| Earnings Reports | earnings, quarter, revenue, beat, miss, guidance |
| Price Actions | high, low, up, down, rally, drop, surge |
| Analyst Ratings | upgrade, downgrade, overweight, neutral, target |
| Market Indices | nasdaq, dow, s&p, futures, session |
| Company Events | acquisition, merger, partnership, launch, approval |

### Sentiment Distribution Analysis
- Compare sentiment across different publishers
- Analyze sentiment trends over time
- Compare sentiment for each stock (AAPL, AMZN, META, NVDA)

### Lagged Correlation Analysis
| Analysis Type | Status | Result |
|---------------|--------|--------|
| Same-day correlation | ✅ Completed | r = 0.1581 (p = 0.2235) |
| Next-day correlation | 🔜 Planned | TBD |
| 3-day forward correlation | 🔜 Planned | TBD |

### Expected Improvements for Final Submission
- Add LDA topic modeling visualizations
- Include sentiment distribution charts
- Calculate lagged correlations
- Compare results across all 4 stocks

  ## 🚀 How to Run
1. Clone this repository
2. Install dependencies: pip install -r requirements.txt
3. Open the Jupyter notebook
4. Run all cells

## 👩‍💻 Author
[Blen Assefa]

## 📅 Date
May 2026
- Scikit-learn

## 📁 Repository Structure
