# Stock_Prediction_Python

Implementation of the Strategies

SMA: We're going to use a very simple indicator first, which is the Simple Moving Averages; the concept for the same is very simple, we take an average of the Close Prices for a certain period to smoothen the trend & depict the general direction of the trend flow.
We have two SMA's, one for a short period; the other is for a long period. We've written a simple function to Buy when the Short MA is more than the long one & Sell when the Long MA is more than the Short one. 

MACD: The Moving Average Convergence Divergence indicator (MACD) is calculated using two exponential moving averages (EMA) - short term and long term. An exponential moving average of MACD is used as a signal line to indicate the upward or downward momentum. An exponential moving average is nothing but simply a moving average that gives more weightage to the recent data.

BB: Bollinger bands are one of the most used indicators in the world of trading, simply because it is so powerful and yet very simple.

They comprise of three lines, Upper Bollinger band, Middle Bollinger band, Lower Bollinger band. The upper and lower Bollinger bands are plotted two standard deviations away from the mean average of the Close Price. The two bands comprise more than 80% of the price action, thus making any price above or below the bands highly significant.
