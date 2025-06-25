FX, Gold, and Oil Price Tracker
This project fetches and combines historical foreign exchange rates, gold prices, and crude oil prices to create a unified dataset for financial analysis.

What It Does
Collects USD exchange rates to:

Nigerian Naira (NGN)

Euro (EUR)

British Pound (GBP)

Retrieves gold prices using gold futures (GC=F)

Retrieves Brent crude oil prices (BZ=F)

Merges everything into a single time-series DataFrame

Exports the combined dataset to historical_data.csv

Technologies Used
Python

Pandas for data manipulation

Requests for API calls

yfinance for financial data

matplotlib (optional) for visualization

Data Sources
FX Rates: Frankfurter.app – free and open API

Gold & Oil: Yahoo Finance via yfinance

Use Cases
Analyzing how gold and oil prices correlate with exchange rates

Studying market behavior over time

Practicing real-world data analysis and API integration
