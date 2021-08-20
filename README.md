# Accenture-stock-price-prediction-using-time-series-analysis
Developed a time series analysis model using Auto Regressive Integrated Moving Average that could predict stock prices for upcoming years. Initially I explored the data and decided to work with data from 2nd January 2015. After that I applied feature engineering to calculate the return value which was Price Difference between two consecutive values divided by closing value of the last day then I calculated moving average value of opening and closing stock. After that I did a prediction with a 70-30 train and test split in which exogenous variables were moving average close and moving average open. Then using ARIMA model I performed step-wise search to minimize AIC and then obtained the best result which was plotted using a graph in which it was compared with real test set.

![image](https://user-images.githubusercontent.com/45181080/130186800-3378d654-4754-41e4-8f4a-c36d0e7f6fb7.png)

