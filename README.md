Algorithmic Trading with Machine Learning

This repository contains a collection of algorithmic trading strategies that leverage machine learning techniques to identify trading opportunities in financial markets. The projects cover a range of strategies from unsupervised learning to sentiment analysis and volatility modeling.

Projects Overview

Project 1: Unsupervised Learning Trading Strategy
This project focuses on developing a trading strategy using unsupervised learning techniques to cluster similar assets and optimize portfolio allocations.

Key Steps:

Download and preprocess SP500 stocks prices data.
Calculate features and indicators, and filter the top 150 most liquid stocks on a monthly basis.
Calculate monthly returns for various time horizons and download Fama-French factors for rolling factor beta calculations.
Employ K-Means clustering for asset grouping and select assets for portfolio construction based on Efficient Frontier optimization.
Visualize portfolio returns and benchmark against the SP500 index.

Project 2: Twitter Sentiment Trading Strategy

Project 3: Intraday GARCH Trading Strategy
This project develops an intraday trading strategy based on GARCH model volatility predictions and intraday price indicators.

Key Steps:

Use simulated daily and intraday (5-minute) data.
Fit a GARCH model on daily data to forecast next day's volatility and generate trading signals.
Merge with intraday data to refine signals based on intraday price movements.
Execute trades based on the signal and hold until the end of the trading day.
Calculate and evaluate the strategy's returns.
Prerequisites

The projects require the following Python packages:

pandas
numpy
matplotlib
statsmodels
pandas_datareader
datetime
yfinance
sklearn
PyPortfolioOpt
Installation

Provide instructions on how to set up the environment and install the necessary packages, e.g., using pip or conda.

