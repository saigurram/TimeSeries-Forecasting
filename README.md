# TimeSeries-Forecasting

![alt text](https://3qeqpr26caki16dnhd19sv6by6v-wpengine.netdna-ssl.com/wp-content/uploads/2018/08/Line-Plot-of-Monthly-Car-Sales.png)

Revenue/Sales forecasting aids any organization in understanding their cash flows. 

1.They can align their performance mertics accordingly. 

2.New investors can be acquired.

3.new products can be launched. 

4.Supply chain can optimze their operations. 

4.Marketing can target their efforts. 

5.Sales can work on discounts, incentives, product bundling etc. 

Understanding the seasonality and the trend variations in the data helps in applying appropriate exponential smoothing techniques. 

Dataset : 

The shampoo sales dataset used in this project can be obtained from Kaggle or from https://raw.githubusercontent.com/jbrownlee/Datasets/master/shampoo.csv.

The data has sales numbers for three consecutive years. Forecasting the sales with respect to time is helpful for any organization in anticipating the Revenue growth.

Objective:

Forecast shampoo sales for any given period.

The Sales_Forecasting pptx and pdf files contain detailed explanation on what techniques/model was used. 

Model:

Used augmented dickey fuller test and seasonal decompose to understand stationarity. Used first order differencing to make the series stationary. Used ARIMA model to generate time series forecasts. 

Summary:

This model can now be used to forecast the shampoo sales for any given period.

Applied exponential smoothing techniques to make the series stationary but first order differentiation worked better. 

Areas of Improvement:

Along with log transformation and rolling statistics other differentiation techniques can be explored.

Other algorithms like LSTM, Prophet can be used to optimize the forecasts.  


