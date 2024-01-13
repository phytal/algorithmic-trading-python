# Algorithmic Trading in Python




## Introductory Project
This part of the project is based on the [freeCodeCamp course](https://github.com/nickmccullum/algorithmic-trading-python). It was aimed to familiarize myself with yfinance, valuation, and the pandas framework.

### Sections
1. Equal-Weight S&P 500 Index Fund
2. Quantitative Momentum Investing Strategy
3. Quantitative Value Investing Strategy

## Unsupervised Learning Trading Strategy
This part of the project is based on the [freeCodeCamp course](https://github.com/Luchkata/Algorithmic_Trading_Machine_Learning/tree/main). 

### Sections
1. Download up-to-date S&P 500 stocks' price data.
2. Calculate the following features and technical indicators for each stock.
    - Garman-Klass Volatility
    - RSI
    - Bollinger Bands
    - ATR
    - MACD
    - Dollar Volume
3. Aggregate to monthly level and filter top 150 most liquid stocks for each month.
4. Calculate Monthly Returns for different time horizons as additional features.
5. Download Fama-French Factors and Calculate Rolling Factor Betas.
6. Fit each month to a K-Means Clustering Algorithm to group similar stocks based on their RSI and ATR.
7. For each month, select stocks based on the cluster and form a portfolio based on Efficient Frontier max sharpe ratio optimization 


## Remarks
The financial data in this project uses real data retrieved from Yahoo! Finance via the yfinance library. This project is not meant to be used as financial advice. 