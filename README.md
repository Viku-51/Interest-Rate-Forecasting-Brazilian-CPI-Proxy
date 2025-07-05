# Interest-Rate-Forecasting-Brazilian-CPI-Proxy
This project aims to forecast the Brazilian interest rate trend using CPI data as a proxy. It applies time series modeling techniques, primarily using the ARIMA model, and includes data visualization, stationarity testing, and performance evaluation. 


# 🧠 Objective 
To demonstrate time series forecasting skills using macroeconomic data relevant to interest rate modeling and financial strategy.

# 📦 Tools Used

- Python

- Pandas, numpy

- matplotlib, seaborn

- statsmodels (ARIMA)

- scikit-learn (RMSE metric)

Key Tasks

* Data Cleaning & Parsing from a publicly available CPI dataset (filtered for Brazil)

* Visualization & ADF Test for stationarity

* ARIMA(1,1,1) Modeling and parameter tuning

* Forecasting future values and plotting projections

* Backtesting using RMSE to measure forecast accuracy

# Forecast graph of Brazil CPI (as proxy for interest rates):
Shows the historical CPI trend and projected future values using ARIMA model. It provides visual insight into inflation expectations and potential rate movement trends.

# ARIMA summary output:
- Displays statistical diagnostics including coefficients, standard errors, confidence intervals, and model fit statistics (AIC, BIC). These values help assess:

- AR/MA coefficients: Indicate the influence of past values and residuals.

- P-values: Help test the statistical significance of each coefficient.

- AIC/BIC: Used to compare model fit; lower values indicate better fit.

- Log Likelihood: Indicates overall fit of the model to the observed data

# RMSE score from backtest to evaluate model performance:
- Evaluate model performance

# 🚀 Future Enhancements

- Replace CPI with actual DI rate or Fed Funds data

- Use monthly frequency for more granular modeling

- Compare ARIMA with Facebook Prophet or LSTM

- Streamlit dashboard for interactive visualization

🔗 Data Source

https://github.com/datasets/inflation

### Vikrant ChandraEmail: vikrantchandra12@gmail.com
### LinkedIn: linkedin.com/in/vikrant-chandra


