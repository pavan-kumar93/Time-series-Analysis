** Hatsun Agro Sales Forecasting using Time Series (ARIMA & SARIMAX)

**Project Overview
This project applies Time Series Analysis and Forecasting techniques on real quarterly sales data of Hatsun Agro Product Ltd. using Python.
The objective is to understand sales trends, check stationarity, and build forecasting models using ARIMA and SARIMAX.

** Tools & Technologies**
Python
Pandas, NumPy
Matplotlib, Seaborn
statsmodels (ADF Test, ARIMA, SARIMAX)
Scikit-learn (RMSE Evaluation)

** Steps Performed **
1. Data Preparation
Loaded quarterly sales data from Excel
Converted date column to datetime format
Set date as time series index

2. Trend & Seasonality Analysis
Visualized original sales trend
Decomposed series using additive model
Plotted rolling mean and rolling standard deviation

3. Stationarity Check
Applied ADF (Augmented Dickey-Fuller) Test
Performed first differencing and seasonal differencing
Verified stationarity before modeling

4. Model Building
ARIMA (2,1,1) for trend-based forecasting
SARIMAX (2,1,1)(2,1,1,4) for seasonal pattern capture

5. Model Evaluation
Compared predictions with actual sales
Evaluated using RMSE
Observed that predictions follow the trend but do not match exact sales values

6. Future Forecast
Forecasted sales for upcoming quarters of 2025

** Key Observations **
Sales show a clear upward trend with seasonal fluctuations.
SARIMAX performs better than simple ARIMA in capturing seasonality.
Forecasted values follow directionally correct patterns but are not exact, which is expected due to:
Limited historical data
Real-world volatility
Simplified parameter tuning

** Learning Outcomes **
Time series preprocessing and visualization
Stationarity testing using ADF
ARIMA & SARIMAX model implementation
Forecast evaluation using RMSE
Real-world application of statistical modeling

👤 Author
Pavan Kumar
MBA in Business Analytics | Aspiring Data Analyst
Skills: SQL, Python, Power BI, Excel, Statistics

** Disclaimer **
Predictions are for learning and academic purposes only and are not intended for financial or business decision-making.

** Acknowledgement **
This project is created for learning and portfolio purposes, inspired by online tutorials and applied on publicly available financial data of Hatsun Agro Product Ltd.