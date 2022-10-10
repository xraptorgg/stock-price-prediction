# Stock Price Prediction using LSTM


Deep Learning Model to predict the closing price of Microsoft using LSTM network. Uses 20+ years of data of Microsoft (ticker: MSFT) stock prices using Yahoo Finance. Neural Network is trained using Huber loss function as it doesnt heavily penalize outliers, and Adam optimizer with a learning rate of 0.002 to counter overfitting and 10 epochs. Achieved a **Mean Absolute Percentage Error of 0.018334989799206575%** on test set, thus the model can generalize well to new data.

The model learns from the closing price data of 29 consecutive days and then predicts the closing price on 30th day


![Prediction on test set](https://cdn.discordapp.com/attachments/954319966444851200/1029084322134757427/unknown.png)
