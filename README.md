# Stock-Performance-Predictor
The goal of this project is to eventually develop a machine learning algorithm that can predict both long-term and near-term trends 
in the stock market. Accurately predicting micro-trends or individual closing prices is likely too complex at the moment, which is
why the project aims primarily at predicting trends on a larger scale. 

This program uses a recurrent neural network composed of a single layer of 100 LSTM cells with an Adam optimizer. The model is 
trained on 2000 NASDAQ closing prices, and is tested on the most recent 31 closing prices. 

Currently, the results are not yet accurate. The model has gotten the overall trend correct, but has predicted the closing prices
inaccurately (a predicted closing price of around 2300 for 26 January, 2018). 
