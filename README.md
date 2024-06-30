Gender Bias in Sentiment Analysis
==============================

Aaricia Herygers, Christian Schneider, Zeqian Wang

Data Science Bootcamp @ DataScientest

==============================

The aim of this project is to see whether the presence of certain gendered words (e.g., "he" or "she") affect the sentiment predicted by certain models. We also compare sentiment across two languages, i.e., English and German, as from a parallel corpus.

We initially used NLTK and GermanSentiment as these are very basic models. We then attempt an analysis with BERT models based on the first data pre-processing for NTLK and GermanSentiment. However, we also found a faster way to make use of the BERT models.

Additionally, we make a first attempt to predict the sentiment differences across the two languages using a Gradient Boost Classifier and a simple Keras dense neural network.

We visualize all sentiments.