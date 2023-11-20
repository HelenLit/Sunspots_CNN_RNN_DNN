# Sunspots_CNN_RNN_DNN
Predicting Sunspots with Neural Networks

This is my laboratory work at the "Sequences, Time Series and Prediction" course. Here, I built and trained model on the [Sunspots](https://www.kaggle.com/datasets/robervalt/sunspots) dataset: a monthly record of sunspot numbers from January 1749 to July 2018. In the previous weeks, I already used DNNs, RNNs, and CNNs to build different models on synthetic data. Here, I tried a combination of these types of networks: the data windows will pass through a convolution, followed by stacked LSTMs, followed by stacked dense layers.

**Dataset preview:**

![image](https://github.com/HelenLit/Sunspots_CNN_RNN_DNN/assets/108334668/ddafb809-098c-4838-9e22-36f7a75cc4c4)


**Model summary:**

![image](https://github.com/HelenLit/Sunspots_CNN_RNN_DNN/assets/108334668/9d8b9e95-e82e-4b90-bcd9-6e5447c6b723)

**Mean absolute error = 14.110082**

**Result of forecasting:**

![image](https://github.com/HelenLit/Sunspots_CNN_RNN_DNN/assets/108334668/07e50437-1a6a-44e1-8a3f-5f9b34c08938)
