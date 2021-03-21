# LSTM Stock Predictor Summary

Using the Crypto Fear and Greed Index (FNG) which attempts to produce daily FNG value for cryptocurrency, we  built and evaluated deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.  The results demonstrated that LSTM, recurrent neural network (RNN) model when using 10-day closing prices of bitcoin, has a
lower loss and tracks the actual values better over time. Lastly, after trying multiple windows sizes for
FNG and closing price models it appeared that for both models lower (<=4) sizes track actual values better than window sizes on the higher end (i.e., 5>=) with closing price model still showing better overall results.


