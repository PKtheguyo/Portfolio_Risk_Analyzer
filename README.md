# Portfolio_Risk_Analyzer
Simulates portfolio and S&P500 variance using block bootstrap in Jupyter Notebook using Python and visualized in PowerBI
Currently simulates 10-year portfolio growth, but year and stock variables can be changed to produce different growth results
Calculates 25th, 50th, and 75th percentile growth bands and Sharpe Ratios for the portfolio and the S&P500
Finds Betas for the portfolio using the 3-Factor Model 
Gathers stock prices from Yahoo Finance and factor data used was obtained from the Kenneth R. French Data Library (https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html)

Uploaded the following CSVs into PowerBI for visualizations:
"bands.csv" containes percentile paths for the portfolio
"bandsSPY.csv" containes percentile paths for the S&P500
"Sharpe.csv" containes Sharpe Ratios for the portofolio and S&P500
"3Factor.csv" containes Beta values for the portfolio

Libraries used:
yfinance 
pandas 
numpy 
statsmodels.api





