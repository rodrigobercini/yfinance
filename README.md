## yfinance fix for fundamentals data

This repo contains a humble attempt at temporarily fixing the [yfinance](https://github.com/ranaroussi/yfinance) package for fetching financial data.

## There are several limitations to this fix

1) I could only fetch consistent data for the US market. For other stock exchanges, please, be sure to validate the data extracted with the official Yahoo Finance Website.

2) As an alternative, I adapted the code by [Matt Button](https://www.mattbutton.com/2019/01/24/how-to-scrape-yahoo-finance-and-extract-fundamental-stock-market-data-using-python-lxml-and-pandas/). Unfortunately, this will only fetch yearly data (no quarterly available). If you need info from other markets than the US, try using the dev branch of this fork:
!pip install https://github.com/rodrigobercini/yfinance@dev

# Highly recommended alternative
If you need financial data, I'd definitely recommend you to check the [yahoo-query](https://github.com/dpguthrie/yahooquery) package by [dpguthrie](https://github.com/dpguthrie/), which seems to be the best API for extracting financial data from Yahoo Finance. The data is available annualy and quarterly

