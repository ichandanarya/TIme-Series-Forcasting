# Time Series Forecasting of Gold Prices :



## 📌 Project Overview
This project focuses on time series forecasting of gold prices using historical monthly data from 1950 to 2020. The objective is to analyze long-term trends, visualize gold price movements, and build forecasting models to predict future prices.

The notebook demonstrates step-by-step preprocessing, visualization, and implementation of statistical forecasting methods.
## 📂 Dataset
Source: gold_monthly_csv.csv (historical gold prices)

Period Covered: January 1950 – August 2020

Frequency: Monthly
## ⚙️ Key Steps in the Notebook
1. Data Loading & Exploration

        Read gold price dataset (pandas)

        Checked data shape, range, and missing values

2. Data Preprocessing

        Converted dates into DatetimeIndex

        Generated monthly and yearly trends

Computed statistical summaries

3. Visualization

        Time series plots of gold prices

        Yearly average trends

        Boxplots and line plots for variability

4. Model Building

        Train-test split (train ≤ 2015, test > 2015)

        Forecasting models applied:

        Simple Exponential Smoothing (SES)

        Holt’s Linear Trend Method

        Exponential Smoothing (Holt-Winters)

        Linear Regression for trend approximation

5. Evaluation

        Calculated Mean Absolute Percentage Error (MAPE)

        Compared forecast vs actual prices

        Constructed confidence intervals for predictions

        Final Forecasting

        Best model selected based on MAPE

        Visualized actual vs predicted values with confidence bands
## 📊 Results

    The project provides insights into long-term gold price trends.

    Forecasting results are visualized with confidence intervals.

    MAPE is used as the performance metric for model accuracy.
## 🛠️ Technologies Used

    Python

Libraries:

    numpy, pandas → Data handling

    matplotlib, seaborn → Visualization

    statsmodels → Time series models

    sklearn → Linear regression
## 🚀 How to Run
Clone the repository:

git clone https://github.com/ichandanarya/time-series-forecasting.git cd time-series-forecasting

## 📌 Future Improvements

        Compare with ARIMA/SARIMA models

        Try Facebook Prophet for seasonality trends

        Incorporate external economic indicators (e.g., inflation, stock indices)
 ✨ This project is a demonstration of time series forecasting techniques applied to real-world financial data.
