# Interim Report - Week 1: News Sentiment Analysis

## Data Loading and Cleaning
- Loaded 1.4 million news articles with no missing values
- Stock price data loaded for AAPL (2009-2024)

## Key EDA Findings
- **Top publishers**: Paul Quintaro (228k), Lisa Levin (187k), Benzinga Newsdesk (150k)
- **Peak news volume**: 2019-2020
- **Most mentioned stocks**: MRK, MS, NVDA, MU, QQQ, NFLX
- **Common keywords**: vs, stocks, eps, market, shares, earnings, price, upgrades

## Technical Indicators (Initial Progress)
- Implemented 20-day and 50-day Simple Moving Averages for AAPL
- Implemented 14-day RSI (Relative Strength Index)
- SMA helps identify trend direction; RSI identifies overbought/oversold conditions

## Challenges Encountered
- Large dataset size (1.4M rows) required sampling for keyword extraction
- Timezone handling for news publication times

## Next Steps for Final Submission
- Add sentiment analysis using TextBlob/VADER
- Correlate sentiment scores with daily stock returns
- Expand to multiple stocks (AMZN, NVDA, GOOG, META)
- Compute MACD and other technical indicators
- Create final report with investment strategy recommendations