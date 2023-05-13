# Stock Price Prediction for Apple Inc. (AAPL)

## Project Overview
The prediction of stock prices is a highly researched area that garners interest from both academia and industry. Our project aims to investigate various techniques for predicting share prices and evaluate their performance based on the obtained results. We will forecast the stock prices of AAPL and evaluate the effectiveness of different modeling techniques based on its data. The historical stock data was collected from Yahoo Finance API between 01-01-2010 to 31-12-2022. We only selected the stock's adjusted closing price for each transaction day. GDP and inflation rate data were collected from The World Bank and based on the USA between 2010 to 2022.

## Methods Used
We utilized the following techniques for stock price prediction:
- Multiple linear regression (MLR): a statistical technique that uses several explanatory variables to predict the outcome of a response variable. It is an extension of simple linear regression that involves more than one explanatory variable.
- Random forest: a commonly-used machine learning algorithm that combines the output of multiple decision trees to reach a single result.
- Long Short-Term Memory (LSTM): an artificial neural network used in the fields of artificial intelligence and deep learning. Unlike standard feedforward neural networks, LSTM has feedback (memory) connections where feedback (memory) is partially retained. LSTMs are designed to avoid the long-term dependency problem that can occur with traditional RNNs.

## Feature Selection
We used the following 10 predictors for our models:
- daily_returns
- 50_day_moving_avg
- 200_day_moving_avg
- volume
- daily_high_low_pct
- 10_day_volume_moving_avg
- 30_day_volume_moving_avg
- rsi
- ema
- GDP
- Inflation

## Train-Test Split
We split our data into train and test using a common splitting ratio of 80:20, which means 80% of the data is for training and 20% for testing.

## Evaluation Metric
We used Mean Squared Error (MSE) to evaluate how well a regression model fits the data. MSE measures the average of the squares of the errors between the estimated values and the actual value. The smaller the MSE, the better the model fits the data.

## Conclusion
Our project aims to investigate various techniques for predicting share prices and evaluate their performance based on the obtained results. We utilized multiple linear regression, random forest, and long short-term memory techniques for stock price prediction. We used 10 predictors for our models and split our data into train and test using a common splitting ratio of 80:20. We used Mean Squared Error (MSE) to evaluate the performance of our models. The results of our analysis are presented in our report.
