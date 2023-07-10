# Disaster Tweets: A text clessification task

This project is among Kaggle competetion projects with aims to classify tweets into two classes: the one that are about a disaster and the one which are not. You can find the dataset [here](https://www.kaggle.com/competitions/nlp-getting-started/overview). We provided two Jupyter Notebook files: one for machine learning algorithms and the other one for deep learning algorithms including Bert and LSTM.

The DisasterTweet file which contians ML algorithms covers all needed process before model training including preprocessing, visualization, and feature engineering. We extracted some useful and meaningful features from the dataset including 

- number of words
- number of sentences
- a binary variable that indicates the tweet contians a specific type of part of speech tagging or not
- an assigned label title generated using topic modelling techniques. 

For all of these new variables, we tested their relationship with the target feature using hypothesis testing. For vectorization, we tested three main vectorization techniques: **Count Vectorize**, **TF-IDF** and **BOW**. We also used **Doc2Vec embedding** techniques to keep the lexical relationship between words into account. This Notebook is self- contianed and a reader can get its process just by following cells.

The DisasterTweet_BertLSTM notebook was created to evalaute the performance of the Bert model and the LSTM model on this dataset. Among all machine learning nad deep learning algorithms BERT returns the best F1 score. We did some required preprocessing steps before feeding data into model. To  gain a better undertanding of the preprocessing step of LSTM model, we provided another notebook named `Preprocessing steps for LSTM` for probable interested readers. 
