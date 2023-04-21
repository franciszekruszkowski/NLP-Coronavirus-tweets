# NLP-Coronavirus-tweets

Coronavirus Tweet Sentiment Analysis
This repository contains a Python script for sentiment analysis on a dataset of coronavirus-related tweets. The script cleans and preprocesses the data, tokenizes and stems the words, and uses the Multinomial Naive Bayes classifier to predict the sentiment of each tweet. Additionally, it provides a word frequency plot for better understanding of the dataset.

Training set accuracy obtained at 82% for 5 classes of tweets (Extremely Negative, Negative, Neutral, Positive, Extremely Positive)

Features
Reads a CSV file containing tweets related to coronavirus
Preprocesses the tweets by converting to lowercase, removing non-alphabetic characters, URLs, and consecutive whitespaces
Tokenizes the tweets into lists of words
Removes stop words and words with less than or equal to 2 characters
Stems the words in the tweets using the PorterStemmer
Trains a Multinomial Naive Bayes classifier on the preprocessed data
Calculates the training accuracy of the classifier
Plots the word frequencies for better understanding of the dataset
