<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Project+Overview;+ARIMA+AND+SARIMA+Model&center=true&size=30&font=Lato&color=blue&speed=20">
  </a>
</h1>

# 📂 **ARIMA-and-Seasonal-ARIMA-Project**

## 📚 *Introduction*
This project focuses on forecasting sales data using time series models, with a particular emphasis on capturing both trend and seasonality patterns. The goal is to evaluate the effectiveness of models such as ARIMA and SARIMA in providing accurate predictions for future sales.

## ⚙️ *Methodology*
ARIMA Model (AutoRegressive Integrated Moving Average)
The ARIMA model is used for forecasting time series data by combining three components:

AR: Autoregressive, using past observations.
I: Integrated, for making the data stationary by differencing.
MA: Moving Average, using past forecast errors.
In this project, we applied an ARIMA(1,1,1) model to capture trends in the sales data, using ACF and PACF plots to determine the optimal AR and MA terms. The model's performance is evaluated with AIC and BIC.

SARIMAX Model (Seasonal ARIMA with Exogenous Variables)
The SARIMAX model extends ARIMA by including seasonal patterns and external factors (exogenous variables). It is ideal for forecasting data with seasonal fluctuations. The model captures both seasonal and non-seasonal trends, improving accuracy. AIC and BIC are used to evaluate its performance.


## 📝 *Summary* 
The analysis revealed that the ARIMA model failed to fully capture the seasonal variations in the sales data, making it less effective for accurate forecasting. By incorporating seasonal components, the SARIMA model demonstrated its ability to better align with the seasonal patterns, resulting in improved model performance for future predictions.
