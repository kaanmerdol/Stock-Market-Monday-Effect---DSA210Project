# Stock-Market-Monday-Effect---DSA210Project
Stock Market Monday Effect - DSA210Project

Project Overview

This project explores the Monday Effect, a stock market anomaly suggesting that stock returns on Mondays differ significantly from other weekdays. Using historical stock data from Yahoo Finance, the goal is to analyze whether Monday returns are systematically lower than other weekdays and determine if traders can adjust their strategies accordingly. By leveraging data visualization, hypothesis testing, and statistical models, this study aims to uncover potential market inefficiencies and investor behavior patterns.

Objectives

Analyze weekly stock market trends to determine if a systematic pattern exists in daily returns.
Conduct hypothesis testing to evaluate whether Monday returns are significantly different from those on other weekdays.
Identify potential factors such as trading volume and investor behavior that may contribute to the Monday Effect.
Apply data science techniques to analyze and visualize stock market data effectively.
Motivation

As a computer science student with a double major in business administration and minors in finance and business analytics, I am interested in applying data-driven methodologies to real-world financial markets. This project allows me to integrate statistical analysis, programming, and business insights to investigate a well-documented market anomaly. By examining stock market inefficiencies through data science techniques, I aim to understand how investors’ trading behaviors influence price movements and whether these patterns can be leveraged for better decision-making.

Analyzing market inefficiencies provides valuable insights for both academic research and practical investing strategies. Identifying systematic patterns in stock returns can help investors make more informed trading decisions. Statistical techniques such as hypothesis testing and regression analysis enable a structured approach to evaluating financial anomalies. Understanding the role of investor behavior and market conditions in stock return fluctuations can lead to improved trading strategies and better financial forecasting.

Dataset

The dataset will be sourced from Yahoo Finance and will include the following variables:

Date: The specific trading day, formatted as YYYY-MM-DD.
Opening Price: The stock price at the market open.
Closing Price: The stock price at the market close.
Daily Return: The percentage change in stock price from the previous day, calculated as:
Daily Return
=
Closing Price
−
Previous Close
Previous Close
×
100
Daily Return= 
Previous Close
Closing Price−Previous Close
​	
 ×100
Weekday: The day of the week associated with each trading session (Monday, Tuesday, etc.).
Trading Volume: The number of shares traded on a given day, reflecting market activity.
Market Index: The stock market index being analyzed, such as the S&P 500 or Nasdaq.
The dataset will be collected for a sufficiently long period to capture both normal market behavior and potential fluctuations in stock return patterns.

Tools and Technologies

The following tools will be used for data collection, analysis, and visualization:

Python: For data extraction, processing, and statistical analysis.
Pandas: For managing and cleaning stock market data.
Matplotlib and Seaborn: For creating visualizations such as box plots, histograms, and time series graphs.
SciPy and Statsmodels: For hypothesis testing, including ANOVA, t-tests, and correlation analysis.
Hypothesis

Primary Hypothesis
H₀: Monday stock returns are not significantly different from those on other weekdays.
H₁: Monday stock returns are significantly different (lower) than those on other weekdays.
Additional Hypotheses
H₂₀: There is no consistent pattern in weekly stock market movements.
H₂₁: Stock returns follow a repeating weekly pattern, with some days having consistently higher or lower returns.
H₃₀: Daily stock returns exhibit random fluctuations without significant autocorrelation.
H₃₁: Stock returns show autocorrelated movements, indicating predictable short-term trends.
H₄₀: Trading volume does not significantly differ between weekdays.
H₄₁: Trading volume is significantly lower on Mondays compared to other days, contributing to lower returns.
H₅₀: The Monday Effect remains consistent across different market conditions.
H₅₁: The strength of the Monday Effect changes during periods of high volatility or economic downturns.
Analysis Plan

1. Data Collection
Historical stock price data will be retrieved from Yahoo Finance using Python’s yfinance library. The dataset will be filtered to exclude non-trading days such as weekends and public holidays. Each trading day will be assigned a corresponding weekday label, and daily returns will be calculated to analyze stock price movements.

2. Visualization
Box plots will be used to compare return distributions for each weekday, providing an overview of stock return patterns. Histograms will illustrate the spread of Monday returns compared to other weekdays. Scatter plots will be employed to track return fluctuations over time, and heatmaps will assess correlations between weekdays and stock returns.

3. Hypothesis Testing
The following statistical tests will be conducted:

ANOVA test: To compare mean returns across all weekdays and determine if differences exist.
Tukey’s HSD test: A post-hoc test to identify which specific weekdays have different return distributions.
Shapiro-Wilk test: To assess whether stock returns follow a normal distribution.
Levene’s test: To evaluate the homogeneity of variance across weekday returns.
4. Trend Analysis
Time series analysis will be performed to determine whether the Monday Effect has changed over time. The effect will be compared across different stock indices such as the S&P 500 and Nasdaq to assess its consistency across markets.

Example Analysis

The following analyses will be conducted:

Box plot of returns by weekday to visualize return distribution patterns for Monday versus other days.
ANOVA and Tukey’s test for weekday returns to identify statistically significant differences.
Time series analysis of Monday returns to assess whether the Monday Effect has weakened or strengthened over time.
Comparison of Monday trading volume versus other weekdays to evaluate whether reduced market activity influences return behavior.
Conclusion

This project aims to answer key questions about stock market behavior. Does the Monday Effect exist in stock market data? Are Monday returns statistically lower than other weekdays? What factors, such as trading volume and investor sentiment, contribute to this phenomenon? Can traders use this information to improve their investment strategies?

By combining finance, data science, and business analytics, this project provides a structured approach to analyzing stock market anomalies. If the Monday Effect is statistically significant, it could offer investors a useful framework for optimizing trading decisions. Through data-driven analysis, this study contributes to understanding market inefficiencies and the behavioral aspects of financial decision-making.
