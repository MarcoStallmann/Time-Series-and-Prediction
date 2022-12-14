# Time-Series-and-Prediction

*by Marco Stallmann*

In this Repository I take a look at some of the unique considerations involved when handling sequential time series data -- where values change over time, like the temperature on a particular day, or the number of visitors to a web site. I am using various methodologies for predicting future values in these time series.

## [Forecasting climate change with NY temperature data](https://github.com/MarcoStallmann/Time-Series-and-Prediction/blob/4ed589dbd2480dc5d6c1274947d2abc9ee04ebad/Forecasting%20climate%20change%20with%20NY%20temperature%20data/Forecasting%20climate%20change%20with%20NY%20temperature%20data.ipynb)
Analysis of New York City average annual temperature data from 1870 to 2016. The data was downloaded from the National Oceanic and Atmospheric Administration (NOAA) website. Using the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) of the data, we fit Autoregression (AR), Moving Average (MA) and ARMA models to the data and use an Information Criterion to choose the best model. With this we can forecast temperatures of the next 30 years.


## [Forecasting with generated time series](https://github.com/MarcoStallmann/Time-Series-and-Prediction/blob/4446dbae38c5dd9ba33aca71860aeec16377d4b8/Forecasting%20with%20generated%20time%20series/Forecasting%20with%20generated%20time%20series.ipynb)

In this Notebook we will be working with time series data. All of the data is going to be generated and we will implement several functions to split the data, create forecasts and evaluate the quality of those forecasts.


## [Predicting time series with Deep Neural Network](https://github.com/MarcoStallmann/Time-Series-and-Prediction/blob/4446dbae38c5dd9ba33aca71860aeec16377d4b8/Predicting%20time%20series%20with%20Deep%20Neural%20Network/Predicting%20time%20series%20with%20Deep%20Neural%20Networks.ipynb)

In the previous Notebook we didn't use machine learning techniques for our forecasts. Here we will be using a Deep Neural Network to create forecasts to see how this technique compares with the ones we already tried out. Once again all of the data is going to be generated.


## [Using RNNs to predict time series](https://github.com/MarcoStallmann/Time-Series-and-Prediction/blob/b0ba369f615d0b005a4017f40112946ececa7e55/Using%20RNNs%20to%20predict%20time%20series/Using%20RNNs%20to%20predict%20time%20series.ipynb)

In the previous Notebook we used a vanilla deep neural network to create forecasts for generated time series. This time we will be using Tensorflow's layers for processing sequence data such as Recurrent layers or LSTMs to see how these two approaches compare.


## [Forecasting Daily Minimum Temperatures in Melbourne dataset](https://github.com/MarcoStallmann/Time-Series-and-Prediction/blob/4446dbae38c5dd9ba33aca71860aeec16377d4b8/Forecasting%20Daily%20Minimum%20Temperatures%20in%20Melbourne%20with%20CNNs/Forecasting%20Daily%20Minimum%20Temperatures%20in%20Melbourne%20with%20CNNs.ipynb)

Here we will be using the Daily Minimum Temperatures in Melbourne dataset which contains data of the daily minimum temperatures recorded in Melbourne from 1981 to 1990. In addition to be using Tensorflow's layers for processing sequence data such as Recurrent layers or LSTMs we will also use Convolutional layers to improve the model's performance.


## [Hybrid models with Store sales time series](https://github.com/MarcoStallmann/Time-Series-and-Prediction/blob/39368774171efc8fb875010d2381aff62d03202c/Hybrid%20models%20with%20Store%20Sales%20time%20series/hybrid-models-with-store-sales.ipynb)

In this Notebook we will create a boosted hybrid for the Store Sales dataset by implementing a new Python class. 
