# STOCK MARKET MONDAY EFFECT - DSA210PROJECT  

## PROJECT OVERVIEW  
This project explores the Monday Effect, a stock market anomaly suggesting that stock returns on Mondays differ significantly from other weekdays. Using historical stock data from Yahoo Finance, the goal is to analyze whether Monday returns are systematically lower than other weekdays and determine if traders can adjust their strategies accordingly. By leveraging data visualization, hypothesis testing, and statistical models, this study aims to uncover potential market inefficiencies and investor behavior patterns.  

## OBJECTIVES  
- Analyze weekly stock market trends to determine if a systematic pattern exists in daily returns.  
- Conduct hypothesis testing to evaluate whether Monday returns are significantly different from those on other weekdays.  
- Identify potential factors such as trading volume and investor behavior that may contribute to the Monday Effect.  
- Apply data science techniques to analyze and visualize stock market data effectively.  

## MOTIVATION  
As a computer science student with a double major in business administration and minors in finance and business analytics, I am interested in applying data-driven methodologies to real-world financial markets. This project allows me to integrate statistical analysis, programming, and business insights to investigate a well-documented market anomaly. By examining stock market inefficiencies through data science techniques, I aim to understand how investors’ trading behaviors influence price movements and whether these patterns can be leveraged for better decision-making.  

Analyzing market inefficiencies provides valuable insights for both academic research and practical investing strategies. Identifying systematic patterns in stock returns can help investors make more informed trading decisions. Statistical techniques such as hypothesis testing and regression analysis enable a structured approach to evaluating financial anomalies. Understanding the role of investor behavior and market conditions in stock return fluctuations can lead to improved trading strategies and better financial forecasting.  

## DATASET  
The dataset will be sourced from Yahoo Finance and will include the following variables:  

- **Date:** The specific trading day, formatted as YYYY-MM-DD.  
- **Opening Price:** The stock price at the market open.  
- **Closing Price:** The stock price at the market close.  
- **Daily Return:** The percentage change in stock price from the previous day, calculated as:  
  ```python
  Daily Return = ((Closing Price - Previous Close) / Previous Close) * 100
