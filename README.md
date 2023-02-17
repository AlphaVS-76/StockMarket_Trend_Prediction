# StockMarket_Trend_Prediction

## Introduction:
The Stocks Market is a common hub where buyers and sellers come together to buy or sell their equity shares in hope of generating a profit. Listed companies offer their shares to get money to improve on their business while the investor hopes for a higher return if the company can make an overall profit. As the buying / selling momentum of the stock market depends drastically on real world affairs, such as political affairs / company profiling / news about the company, it is highly unpredictable and non-linear, meaning that predicting the stock market becomes a very wearisome and mundane task. To completely understand the intel provided by the stock market, Data scientists and analysts use various Machine Learning and Deep Learning techniques. Financially, to predict the stock market we use an analysis technique known as Fundamental Analysis which includes numerous indicators like EPS, P/E ratio, RoE ratio, etc.

## Algorithms Used:
- CNN: A convolutional neural network (CNN or convnet) is a subset of machine learning. It is one of the various types of artificial neural networks which are used for different applications and data types. CNN is suitable for forecasting time-series because it offers dilated convolutions, in which filters can be used to compute dilations between cells.

- LSTM: Long short-term memory (LSTM) is an artificial neural network used in the fields of artificial intelligence and deep learning. LSTMs can be used to model univariate time series forecasting problems. These are problems comprised of a single series of observations and a model is required to learn from the series of past observations to predict the next value in the sequence.

- GAN: A generative adversarial network (GAN) is a class of machine learning frameworks. Two neural networks contest with each other in the form of a zero-sum game, where one agent's gain is another agent's loss. The core idea of a GAN is based on the "indirect" training through the discriminator, another neural network that can tell how "realistic" the input seems, which itself is also being updated dynamically. GAN helps in time series forecasting very accurately.

## Observations/Results:
Finally, we can observe that our proposed model has successfully predicted trend in the stock market with over 100+ listed companies in NSE and figures below summarize our findings in accordance with our training results. 

<img src="https://github.com/AlphaVS-76/StockMarket_Trend_Prediction/blob/main/table.jpg" width="500px">
<img src="https://github.com/AlphaVS-76/StockMarket_Trend_Prediction/blob/main/train.jpg" width="500px">
<img src="https://github.com/AlphaVS-76/StockMarket_Trend_Prediction/blob/main/test.jpg" width="500px">

The best output of the proposed model happened to be approximately 64.29% as a result of numerous trial and error regarding the neural network layers positioning for the generator and discriminator model.
