# PAIR-WISE-ALGORITHMIC-TRADING WITH COINTEGRATION ANALYSIS

# Objective of the Analysis

To implement a Pairs Trading Strategy using statistical and technical indicators.
Analyze the relationship between ^RUT (Russell 2000) and HG=F (Copper Futures).
Develop entry and exit signals based on Z-score and technical indicators.
Evaluate strategy performance using equity curves and metrics like Sharpe Ratio

# Data Collection

Source: 
USSC2000.IDXUSD & COPPER.CMDUSD FROM YAHOO FINANCE

Time Period: 
January 2020 - August 2024

Data Frequency:
Daily

Assets Used:
RUT: Russell 2000 Index
HG=F: Copper Futures

Statistical Analysis

Log Transformation: 
Log-transformed prices for linearity.

OLS Regression:
Dependent Variable (Y): Copper Futures (^HG=F)
Independent Variable (X): Russell 2000 (^RUT)

Spread Calculation:
Spread = Y - (alpha + beta * X)
Rolling Z-score to normalize the spread



<img width="506" alt="image" src="https://github.com/user-attachments/assets/7f70d79e-fb77-4bab-9bc6-4e5cee8e7a01" />



