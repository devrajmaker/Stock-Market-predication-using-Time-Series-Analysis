# Stock Market Prediction Using Time Series Analysis

## Background
The stock market is a volatile and complex market, influenced by numerous factors. Stock price prediction is a valuable skill that empowers investors, financial analysts, and data scientists to make data-driven decisions. This project examines historical stock market data to uncover patterns and factors that influence stock price movement, with a specific focus on time series modeling techniques. These findings aim to help investors predict future trends and assess risk levels.

## Research Questions
1. What indicators are most responsible for stock price movement based on the chosen dataset?
2. How accurately can the closing price of the stock be predicted using historical data and technical analysis?
3. What patterns in volume and price changes correspond to high or low-performance periods?

## Literature Review
1. **Efficient Capital Markets: A Review of Theory and Empirical Work** by E.F. Fama (1970): Introduces the Efficient Market Hypothesis, asserting that "stock prices reflect all available information." While the hypothesis highlights the challenge of market prediction, this project explores the practical predictability of stock prices using historical and technical indicators.
2. **A Prediction-Based Clustering Algorithm for Stock Market Trading** by P.E. Tsinaslanidis and D. Kugiumtzis (2017): Applies clustering techniques to categorize behaviors in stock prices, identifying patterns for future predictions. This research provides insights into machine learning applications for predicting market movements.

## Dataset
- **Primary Dataset**: Yahoo Finance Stock Market Data  
  - **Source**: [Kaggle - Time Series Forecasting with Yahoo Stock Prices](https://www.kaggle.com/datasets/arashnic/time-series-forecasting-with-yahoo-stock-pri)  
  - **Description**: Daily historical stock prices, including columns for Date, Open, High, Low, Close, Volume, and Adjusted Close. This dataset enables the exploration of price trends, volume fluctuations, and future value predictions.

## Methodology
### 1. Data Preprocessing and Exploration
- Clean and preprocess data using pandas.
- Handle missing values, remove outliers, and engineer features like moving averages and the relative strength index (RSI).

### 2. Exploratory Data Analysis (EDA)
- Visualize stock trends over time using matplotlib and seaborn.
- Analyze the price-volume-volatility relationship.
- Plot daily return distributions to understand stock performance variability.

### 3. Feature Engineering
- Compute technical indicators such as:
  - Moving averages (MA)
  - Exponential moving averages (EMA)
  - Volume-based indicators

### 4. Modeling and Prediction
- **Linear Regression**: Baseline model for predicting stock closing prices.
- **Logistic Regression**: Classify high and low performance based on percentage price variation.
- **Time Series Analysis**:
  - Apply rolling statistics to analyze trends and seasonality.
  - Compare ARIMA and SARIMA models to identify the best fit.
- **Cross-Validation**: Use techniques like k-fold cross-validation to ensure model robustness.

### 5. Visualization and Dashboard
- Visualize time series stock performance with matplotlib and Plotly.
- Create an interactive dashboard in Jupyter Notebook to display trends and indicators.

## Preliminary Progress
- The dataset contains key columns (Date, Open, High, Low, Close, Volume, Adjusted Close) essential for stock price analysis.
- Technical indicators have been identified for feature engineering and model development.

## References
1. E.F. Fama, "Efficient Capital Markets: A Review of Theory and Empirical Work," *The Journal of Finance*, 25.2 (1970), pp. 383–417.  
2. P.E. Tsinaslanidis and D. Kugiumtzis, "A Prediction-Based Clustering Algorithm for Stock Market Trading," *Expert Systems with Applications*, 80 (2017), pp. 115–123.

---

## Repository Contents
- **Data**: Contains the primary dataset from Yahoo Finance.
- **Notebooks**: Includes Jupyter Notebooks for preprocessing, EDA, modeling, and visualization.
- **Results**: Comparative analysis of ARIMA and SARIMA models, along with visualizations.
- **Dashboard**: Interactive dashboard showcasing stock trends and indicators.

## Conclusion
This project provides insights into stock price movements using time series analysis, comparing ARIMA and SARIMA models to determine the best fit. The findings and tools developed here aim to assist in data-driven decision-making for investors and analysts.

