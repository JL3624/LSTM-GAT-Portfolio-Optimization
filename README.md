# LSTM-GAT for Portfolio Optimization

This project implements an end-to-end deep learning framework that combines **Long Short-Term Memory (LSTM)** networks and **Graph Attention Networks (GAT)** to predict daily portfolio allocations for a fixed set of U.S. stocks. The model integrates both **price-based features** and **news sentiment data** to optimize for risk-adjusted returns.

## 📈 Project Summary

We directly model portfolio weights (rather than predicting returns) for nine large-cap U.S. stocks across six sectors:

- **Information Technology**: Apple (AAPL), Nvidia (NVDA)
- **Health Care**: Johnson & Johnson (JNJ), Thermo Fisher Scientific (TMO)
- **Consumer Discretionary**: Tesla (TSLA), Amazon (AMZN)
- **Industrials**: Boeing (BA)
- **Consumer Staples**: Costco (COST)
- **Energy**: Valero Energy (VLO)

Using historical stock prices and news sentiment signals, our model learns to allocate daily portfolio weights that improves return while managing volatility.

> Our model achieves an **annualized Sharpe ratio of up to 1.15** and **annualized return of up to 31.23%**, outperforming both the **equal-weighted** portfolio and **CAPM-based mean-variance optimization**.

## 🎯 Project Objectives
The objective of this project is to develop and evaluate a deep learning model that can optimally allocate wealth across multiple assets using both price-based and sentiment-driven signals. Specifically, we aim to assess whether a hybrid LSTM-GAT architecture can outperform traditional portfolio strategies such as equal-weighted and mean-variance optimized portfolios. We also explore the role of financial news sentiment in enhancing model robustness and improving risk-adjusted returns, particularly during periods of market uncertainty.
