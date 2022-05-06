# Investopedia General Market Indices

This repository calculates the daily percent change and overall change in price of these 6 US financial indices:
Dow Jones Industrial Average, CBOE Volatility Index, Nasdaq Composite Index, Bitcoin, S&P 500, and US Treasury Yield 10 Years.

Data is gathered every hour from `yfinance` the [Python wrapper](https://pypi.org/project/yfinance/) for the [Yahoo Finance API](https://blog.api.rakuten.net/api-tutorial-yahoo-finance/). Data is then compiled into the CSV file `worldmarketIndices.csv` and used for a [Datawrapper](https://app.datawrapper.de) visualization in the [Investopedia](https://investopedia.com) daily newsletter. The data in the CSV file is updated at just after US market close (4pm EST).