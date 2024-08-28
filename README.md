# Movie Review Rating 

This project is a sentiment analysis application that uses a Random Forest classifier to predict the sentiment (positive or negative) of movie reviews from the IMDB dataset. The project includes data preprocessing, feature extraction using TF-IDF vectorization, model training, hyperparameter tuning, and model evaluation.

## Overview

The aim of this project is to develop a machine learning model capable of identifying the sentiment expressed in movie reviews as either positive or negative. This can help businesses and individuals understand customer feedback and make informed decisions based on public sentiment.

## Dataset

The project uses the [IMDB Movie Reviews dataset](https://ai.stanford.edu/~amaas/data/sentiment/), which consists of 50,000 movie reviews labeled as either 'positive' or 'negative'. The dataset is split evenly into 25,000 training and 25,000 testing samples.

## Features

- **Data Preprocessing**: Removes duplicates, cleans HTML tags, removes stopwords...
- **TF-IDF Vectorization**: Converts text data into numerical feature vectors using TF-IDF.
- **Model Training**: Trains a model for binary sentiment classification using RandomForestClassifier.
- **Hyperparameter Tuning**: Optimizes model parameters using GridSearchCV.
- **Model Evaluation**: Measures some performance metrics and visualizes with a confusion matrix and a feature importances plot.
