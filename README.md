# Gold-Price-Prediction-An-ARIMA-Model-Approach
Welcome!

# Gold Price Prediction: An ARIMA Model Approach

## Overview
This project focuses on predicting gold prices using time series analysis with an ARIMA (Autoregressive Integrated Moving Average) model. By analyzing historical gold price data, we aim to uncover trends, patterns, and relationships with key economic indicators such as the S&P 500. The insights generated can assist in understanding gold's behavior as a global asset and its implications for investment strategies.

## Project Objectives
- **Time Series Analysis:** Explore historical trends and patterns in gold prices.
- **Trend Identification:** Identify long-term trends, seasonality, and volatility in the data.
- **Deliverables:**
  - Time series visualizations illustrating gold price patterns.
  - Predictive models for future gold price forecasting.

## Why Analyze Gold Prices?
Gold is a globally significant asset with diverse applications:
1. **Time-Series Data:** Offers rich temporal data for analysis.
2. **Global Asset:** Acts as a store of value and hedge against inflation.
3. **Diversification:** Adds stability to investment portfolios.
4. **Macroeconomic Indicators:** Reflects economic health.
5. **Currency Movements:** Inversely correlated with major currencies.

## Dataset Overview
- **Source:** [Kaggle](https://www.kaggle.com)
- **Time Period:** July 2021 - October 2023
- **Records:** 622 daily observations
- **Key Variables:** Open, High, Low, Close prices, Change in Pips, and Change Percentage

## Methodology
### 1. Initial Setup and Exploratory Data Analysis (EDA)
- **Data Cleaning:** Remove null values and handle outliers.
- **Visualization:** Identify trends, seasonality, and volatility using time series plots.

### 2. ARIMA Modeling
- **Model Selection:** ARIMA was chosen to handle non-stationary data trends.
  - **AR (Autoregressive):** Dependency on past values.
  - **I (Integrated):** Differencing to remove non-stationarity.
  - **MA (Moving Average):** Dependency on residual errors.
- **Residual Analysis:** Evaluate the model's performance by analyzing forecast errors.

### 3. Model Testing and Results
- **Data Split:** 80% for training, 20% for testing to avoid overfitting.
- **Predictions:** Compare actual vs. predicted prices with time series plots.
- **Moving Averages:** Analyze price trends with 50-day SMA and 200-day SMA to identify key moments like Golden Cross and Death Cross.

### 4. Correlation Analysis with S&P 500
- **Positive Correlation:** Examine gold prices' relationship with S&P 500 using regression plots.
- **Outliers:** Identify periods where gold prices diverged from S&P 500 movements.

## Key Findings
- **Best Model:** ARIMA(0,1,3) effectively captured gold price trends with low error metrics (MSE, MAPE).
- **Volatility Analysis:** Significant price volatility observed in early 2022 and late 2023.
- **Correlation:** Slight positive correlation with S&P 500, though scattered data highlighted independent movement during certain periods.

## Conclusion
The ARIMA model demonstrates strong predictive capability for gold prices, providing valuable insights for investment and economic analysis. Future work could incorporate additional macroeconomic variables to refine the model further.

## References
1. [Gold Price Prediction Using ARIMA - Kaggle](https://www.kaggle.com/code/vanooshenzr/gold-price-prediction-using-arima/input)
2. [S&P 500 Historical Data - Nasdaq](https://www.nasdaq.com/market-activity/index/spx/historical?page=1&rows_per_page=10&timeline=y5)

