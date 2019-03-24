# Hate-Speech-Detection

This project aims to detect hate speech on twitter. The goal is to leverage user information, in addition to text, to predict if a tweet is hateful or not. The classifier is a feed forward neural network, built with Tensorflow. It will input word embeddings of the tweet's text and a feature vector with information about the user. The model architecture is fixed, and I vary the features in the user feature vector to find the best set of predictors.
