# Spaceship Titanic Prediction

## Project Overview

This project predicts whether passengers were transported to an alternate dimension using machine learning.

## Dataset

* Train samples: 8693
* Test samples: 4277

## Data Preprocessing

* Missing value handling
* Cabin feature splitting (Deck, CabinNum, Side)
* One-hot encoding using pandas get_dummies()
* Boolean feature conversion

## Feature Engineering

* Extracted Deck, CabinNum, and Side from Cabin column
* Removed PassengerId and Name
* Applied one-hot encoding to categorical features

## Model

Random Forest Classifier

## Results

* Kaggle Leaderboard Rank: ~1500
* Evaluation Metric: Accuracy

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Google Colab
