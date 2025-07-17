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

## 📂 Files

### `Literature_Review.pdf`  
This document provides a detailed review of prior research relevant to our project. It focuses on three key papers, analyzing the methodologies, strengths, and limitations of each. The discussion highlights how these works informed our modeling choices.

### `Model_Result_and_Discussion.pdf`  
This report presents the results of five different versions of our proposed model. It includes comprehensive evaluation metrics such as total return, annualized return, volatility, Sharpe ratio, Value at Risk (VaR), and maximum drawdown. It also contains time-series plots of cumulative returns and predicted portfolio weights across the test period. Each model version is discussed in detail, with analysis of performance, design choices, and their implications. The document also includes a section outlining limitations and directions for future improvement.

### `Poster_Final.pdf`  
This is the final project poster summarizing our work . It provides an overview of the project's motivation, data sources, model architecture, feature engineering, graph structure design, and key results. 

## 👥 Authors & Contact

- **Yun Lin**  
  📧 yl5852@barnard.edu  
  🔗 [LinkedIn](https://www.linkedin.com/in/yun-lin39)

- **Jiawei Lou**
- 
  📧 jl6685@barnard.edu  
  🔗 [LinkedIn](https://www.linkedin.com/in/jiawei-lou)

- **Jinghe Zhang**  
  📧 jz3893@columbia.edu  
  🔗 [LinkedIn](https://www.linkedin.com/in/jinghe-zhang-b4468720b/)

