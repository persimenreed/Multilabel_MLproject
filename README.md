# Multilabel_MLproject
ML project on real hydroelectric power data. *LSTM.ipnb* is an approach using sequencial data for predicting the next datapoint. As the dataset is not time-series, the model fails improve in the predictions of true labels through learning. There are probanbly several steps that could have been done to improve this, as I am using a very simple LSTM architecture, but I tried implementing the MLP instead.

*MLP.ipynb* performs well on the dataset. From the regression line, we can see the predictions fit closely to the actual labels. This network is also a very simple NN architecture, and some simple configurations could have improved the result even further. From the output we can see *y1* was the hardest to predict, and the rest of the output labels performing fairly similar on the test set.
