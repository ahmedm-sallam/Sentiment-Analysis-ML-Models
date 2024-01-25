# Sentiment-Analysis-ML-Models

Sentiment analysis using machine learning models to classify text into positive or negative sentiments. and the goal is to build and compare the performance of different models for sentiment classification.

## Dataset Overview

The dataset contains messages from various sources, with corresponding labels indicating positive (1) or negative (0) sentiment. The dataset has been preprocessed to prepare it for training machine learning models.

## Preprocessing

The text data has undergone preprocessing, including converting to lowercase, lemmatization, and removing stopwords using spaCy. The processed text has been vectorized using the CountVectorizer.

## Models

### Linear Support Vector Classification (LinearSVC)

- A Linear Support Vector Classification model has been trained using the CountVectorizer-transformed text data. 
- GridSearchCV was used to find the best hyperparameter (C) for the model.
- Trained using a Bag-of-Words approach with CountVectorizer.
- Best hyperparameter (C) determined through GridSearchCV.
- Achieved an accuracy of 81.55%.

### Artificial Neural Network (ANN)

- An Artificial Neural Network model with one hidden layer has been implemented using MLPClassifier. 
- The model was trained on the vectorized text data.
- Achieved an accuracy of 76.94%.

## Model Comparison

- The performance of the LinearSVC and ANN models has been evaluated in terms of accuracy and classification reports.

## Choosing the Best Model

- The model with the highest accuracy on the test set has been chosen as the best model for this sentiment analysis task.
