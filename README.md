# Interest-Rate-Forecasting-Brazilian-CPI-Proxy
This project aims to forecast the Brazilian interest rate trend using CPI data as a proxy. It applies time series modeling techniques, primarily using the ARIMA model, and includes data visualization, stationarity testing, and performance evaluation. 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/viku-51/Interest-Rate-Forecasting-Brazilian-CPI-Proxy/interest_rate_forecasting_FINAL.ipynb)


## 🧠 Objective 
To demonstrate time series forecasting skills using macroeconomic data relevant to interest rate modeling and financial strategy.

## 📦 Tools Used

- Python

- Pandas, numpy

- matplotlib, seaborn

- statsmodels (ARIMA)

- scikit-learn (RMSE metric)

### 📊 Key Tasks

* Data Cleaning & Parsing from a publicly available CPI dataset (filtered for Brazil)

* Visualization & ADF Test for stationarity

* ARIMA(1,1,1) Modeling and parameter tuning

* Forecasting future values and plotting projections

* Backtesting using RMSE to measure forecast accuracy

### Forecast graph of Brazil CPI (as proxy for interest rates):
Shows the historical CPI trend and projected future values using ARIMA model. It provides visual insight into inflation expectations and potential rate movement trends.

### ARIMA summary output:
- Displays statistical diagnostics including coefficients, standard errors, confidence intervals, and model fit statistics (AIC, BIC). These values help assess:

- AR/MA coefficients: Indicate the influence of past values and residuals.

- P-values: Help test the statistical significance of each coefficient.

- AIC/BIC: Used to compare model fit; lower values indicate better fit.

- Log Likelihood: Indicates overall fit of the model to the observed data

### RMSE score from backtest to evaluate model performance:
- Evaluate model performance

![image](https://github.com/user-attachments/assets/b0b50bf7-57f9-4fcc-9117-098b44ff7524)

![image](https://github.com/user-attachments/assets/25ee4173-74c9-445c-bb8c-deb632cbccd6)

![image](https://github.com/user-attachments/assets/892c867f-4fd2-4782-8f17-12c0eedb9fac)

![image](https://github.com/user-attachments/assets/60a09d75-8c20-4124-b190-b64ff387216a)

![image](https://github.com/user-attachments/assets/318eb734-35e4-48ab-bac6-167ab96026ef)

![image](https://github.com/user-attachments/assets/683c05f4-d29d-4d3b-ba5a-c0e19af2c24e)

![image](https://github.com/user-attachments/assets/1956b835-5466-4647-9896-039a93b966e9)

![image](https://github.com/user-attachments/assets/612adf6f-661a-4e7b-b711-a4d04a1bb61f)

![image](https://github.com/user-attachments/assets/131ddb7e-38e1-416c-bbe6-f1ae6092c9f0)


## 🚀 Future Enhancements

- Replace CPI with actual DI rate or Fed Funds data

- Use monthly frequency for more granular modeling

- Compare ARIMA with Facebook Prophet or LSTM

- Streamlit dashboard for interactive visualization

### 🔗 Data Source

https://www.investing.com/economic-calendar/brazilian-cpi-410

### Vikrant Chandra
Email: vikrantchandra12@gmail.com
### LinkedIn: linkedin.com/in/vikrant-chandra


