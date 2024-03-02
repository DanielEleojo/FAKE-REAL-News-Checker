# FAKE-REAL-News-Checker
# Introduction

Using a Support Vector Machine, I'm setting up a classification task by going through a test database on a file. This file is used to train and test the module of what real and fake news are.
In order words, This Python script is for training a linear support vector machine (SVM) classifier using TF-IDF vectorization on a dataset of news articles labeled as real or fake. Then, it makes predictions on a new text document.

# Implementation

1. Imports necessary libraries:
   - numpy and pandas for data manipulation.
   - train_test_split from sklearn.model_selection for splitting the data into training and testing sets.
   - TfidfVectorizer from sklearn.feature_extraction.text for converting text data to TF-IDF vectors.
   - LinearSVC from sklearn.svm for training a linear support vector classifier.
   - Reads the dataset from a CSV file named "fake_or_real_news.csv" into a pandas DataFrame.
2. Converts the labels in the DataFrame to binary format: 0 for "REAL" and 1 for "FAKE".
3. Drops the original label column from the DataFrame.
4. Splits the dataset into training and testing sets, with 80% of the data used for training and 20% for testing.
5. Initializes a TF-IDF vectorizer with English stop words and a maximum document frequency of 0.7.
6. Vectorizes the training and testing text data using the TF-IDF vectorizer.
7. Initializes a linear support vector classifier.
8. Trains the classifier using the vectorized training data and corresponding labels.
9. Calculates and prints the accuracy score of the classifier on the vectorized testing data.
10. Reads the text from a file named "mytext.txt".
11. Vectorizes the text using the same TF-IDF vectorizer used for the training and testing data.
12. Makes a prediction on the vectorized text using the trained classifier.


> #### An update to the implementation due





















