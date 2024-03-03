# Project Title: SPY Volatility Forecasting using GARCH

This repository contains a Python implementation of volatility forecasting for the SPY ETF using GARCH time series modeling techniques. 
# For further details on the methodology, analysis, and conclusions, please refer to the [PDF project report](./SPY_Volatility_Prediction_using_GARCH_Project_Report.pdf)

## Project Overview

The goal of this project is to accurately forecast volatility for the SPY ETF. By leveraging the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) model, this project analyzes historical volatility patterns to predict future volatility levels.

Volatility forecasting provides crucial insights into market risk dynamics and has applications in areas such as algorithmic trading, portfolio optimization, and risk management.

## Methodology

The key steps involved in this volatility forecasting project are:

- Download and prepare SPY historical price data 
- Calculate daily log returns from prices
- Then plot the PACF plot of the returns
- Based on PACF plot select and fit a GARCH(p,q) model 
- Perform rolling predictions to forecast next-day volatility
- Evaluate model performance against actual observed values

## Contents

This repository contains the following files:

- Jupyter notebook showing the Python implementation of the GARCH model
- Project Report

## Applications

The volatility forecasts obtained from this modeling approach can be integrated into:

- Algorithmic trading systems  
- Portfolio risk management
- Options trading strategies
- Financial forecasting dashboards

Overall, this project demonstrates how GARCH models can provide actionable insights into market uncertainty.
