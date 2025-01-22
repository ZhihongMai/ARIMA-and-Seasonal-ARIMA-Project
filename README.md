<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Project+Overview;+ARIMA+AND+SARIMA+Model&center=true&size=30&font=Lato&color=blue&speed=20">
  </a>
</h1>

# 📂 **ARIMA-and-Seasonal-ARIMA-Project**

## 📚 *Introduction*
This project focuses on forecasting sales data using time series models, with a particular emphasis on capturing both trend and seasonality patterns. The goal is to evaluate the effectiveness of models such as ARIMA and SARIMA in providing accurate predictions for future sales.

## ⚙️ *Methodology*
### ARIMA Model (AutoRegressive Integrated Moving Average)
- **AR (Autoregressive)**: Uses past observations to predict future values.
- **I (Integrated)**: Makes the data stationary by differencing.
- **MA (Moving Average)**: Uses past forecast errors to make predictions.
- In this project, we used **ARIMA(1,1,1)** to capture trends in the sales data, determined by **ACF** and **PACF** plots.
- Model performance is evaluated using **AIC** and **BIC**.

### SARIMAX Model (Seasonal ARIMA with Exogenous Variables)
- Extends ARIMA by including **seasonal patterns** and **external variables**.
- Ideal for forecasting with **seasonal fluctuations** and capturing both **seasonal** and **non-seasonal** trends.
- Performance is evaluated using **AIC** and **BIC**.


## 📝 *Summary* 
The analysis revealed that the ARIMA model failed to fully capture the seasonal variations in the sales data, making it less effective for accurate forecasting. By incorporating seasonal components, the SARIMA model demonstrated its ability to better align with the seasonal patterns, resulting in improved model performance for future predictions.
