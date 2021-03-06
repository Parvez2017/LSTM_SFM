## LSTM - Stock Price Prediction 
I have just read a paper on SIGKDD 2017 about stock price prediction, named Stock Price Prediction via Discovering Multi-Frequency Trading Patterns. And implemented a LSTM version on the 50 stock dataset they provided.

Please read my

[Report PDF](https://github.com/RenXiangyuan/LSTM_SFM/blob/master/stock-prediction-lstm.pdf) 

for detail information about the stock prediction on LSTM and SFM.

* Language: Python 2.7
* Framework: Keras
* Backend: Theano 

SFM is a model that can make predictions on different strategies, short term or long term. It make prediction on users' choice. For example, those looking at a long period investment may use long term strategy.

However, it is accurate enough in term of Mean Square Error but It Doesn't work!

The model will always yield a prediction after the changes have happened, e.g. the stock A turns from rise to fell in Monday, but the model can only realize this change after the change has happened. This make me thinking about whether time series have been used for prediction.

## ARIMA - Bitcoin Price Prediction
I have cooperated with Shiyi Wang, using LSTM and ARIMA to predict Bitcoin Prices.
We get the data using the Bitfinex API.
The codes are included in the file named "Bitcoin"
Please read my

[Report PDF](https://github.com/RenXiangyuan/LSTM_SFM/blob/master/Bitcoin/Bitcoin%20Price%20Time%20Series%20Prediction%20Using%20ARMA%20%26%20LSTM%20Model.pdf) 

for detail information about the Bitcoin prediction on LSTM and ARMA.
