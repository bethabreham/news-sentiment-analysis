# News Sentiment Analysis - Week 1

## Project Overview
Analysis of financial news headlines and their correlation with stock price movements using NLP and technical indicators.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/bethabreham/news-sentiment-analysis.git
   cd news-sentiment-analysis
2. Create and activate virtual environment:
   ```bash
   python -m venv venv
   venv\Scripts\activate
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

## Project Structure
<<<<<<< HEAD
=======
```
>>>>>>> task-1
news-sentiment-analysis/
├── .github/workflows/
│   └── unittests.yml
├── .vscode/
│   └── settings.json
├── data/
│   └── raw/
│       ├── news_data.csv
│       ├── AAPL.csv
│       ├── AMZN.csv
│       ├── GOOG.csv
│       ├── META.csv
│       └── NVDA.csv
├── notebooks/
│   ├── task1_eda.ipynb
│   ├── task2_technical_indicators.ipynb
│   └── task3_sentiment_correlation.ipynb
├── src/
├── scripts/
├── tests/
├── .gitignore
├── requirements.txt
└── README.md
<<<<<<< HEAD
=======
```
>>>>>>> task-1

### Key Findings (Task 1 - EDA)

**Dataset size:** 1.4 million news articles (2011-2020)
<<<<<<< HEAD
**Top publishers:** Paul Quintaro (228k), Lisa Levin (187k), Benzinga Newsdesk (150k)
**Peak news volume:** 2019-2020
**Most mentioned stocks:** MRK, MS, NVDA, MU, QQQ, NFLX
=======

**Top publishers:** Paul Quintaro (228k), Lisa Levin (187k), Benzinga Newsdesk (150k)

**Peak news volume:** 2019-2020

**Most mentioned stocks:** MRK, MS, NVDA, MU, QQQ, NFLX

>>>>>>> task-1
**Common keywords:** "stocks", "earnings", "market", "shares", "price", "upgrades"

### Technical Indicators (Task 2)

Implemented for AAPL stock (2009-2024):
<<<<<<< HEAD
**Simple Moving Average (20-day and 50-day)**
=======

**Simple Moving Average (20-day and 50-day)**

>>>>>>> task-1
**RSI (Relative Strength Index - 14-day)**

## Next Steps (Task 3 - In Progress)

- Sentiment analysis using TextBlob/VADER
- Correlation between news sentiment and stock returns
- Investment strategy recommendations

## CI/CD
GitHub Actions runs tests on every push to main branch.

## Dependencies

- pandas, numpy, matplotlib, seaborn
- textblob, nltk (sentiment analysis)
- yfinance (stock data)
- ta-lib, pynance (technical indicators)
- scikit-learn (NLP features)

## Author

Beth Abraham - 10 Academy KAIM 9 Cohort

## License

<<<<<<< HEAD
This project is for educational purposes as part of the 10 Academy training program.
=======
This project is for educational purposes as part of the 10 Academy training program.
>>>>>>> task-1
