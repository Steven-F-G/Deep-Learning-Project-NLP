# Deep-Learning-Project-NLP
Semester 6 Deep Learning NLP Mini Project-3

**Introduction:**
The problem taken here is to analyze sentiments given in the dataset
consisting of tweets posted during the pandemic. Here the tweets are
labelled as ‘Negative, Neutral and Positive’. Here we implement our
model using an LSTM. LSTM helps to retain memory and does not suffer
from vanishing gradients. We also use the nltk library for preprocessing
the data such as to remove unwanted data and to preserve only the
words that will help to train the model. The aim here is to see how well
we can train the model and see how well it predicts the sentiments of
unseen tweets.


**Dataset Details:**
TThis dataset contains tweets posted during the Coronavirus pandemic.
The tweets have been pulled from Twitter and manual tagging has been
done to them. For training the tweets have been labelled with
sentiments. The sentiments are ‘Negative, Neutral and Positive’. There
are about 41,000 tweets which will be split for training and testing
purposes. All tweets are pulled from Twitter as is, so data preprocessing
will have to be done.

https://www.kaggle.com/datatattle/covid-19-nlp-text-classification
