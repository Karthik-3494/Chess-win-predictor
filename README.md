# chess-win-prediction
Machine learning project that predicts the outcome of a chess game based on player and opponent ratings using Chess.com API data. Implements data collection, preprocessing, and a RandomForestClassifier model to classify match results.

Chess Win Prediction 
=====================

Predict whether a player will win a chess game based on their rating and their opponent’s rating, using data from the Chess.com API.

Project Overview
================

This project uses machine learning to classify chess match results.
The pipeline involves:

Data Collection – Fetching past game data from Chess.com API.

Data Processing – Extracting relevant features:

Player rating

Opponent rating

Match result (win/loss/draw)

Model Training – Using RandomForestClassifier to predict game outcomes.

Tech Stack
===========

Python

Pandas – Data manipulation

Requests – API calls

Scikit-learn – Machine learning model

Chess.com API – Data source

 How to Run
============

Clone the repo

git clone https://github.com/Karthik-3494/chess-win-prediction.git

Model Performance
=================

Model: RandomForestClassifier

Accuracy: ~63% (baseline – can be improved with more features like opening moves, time control, etc.)

Future Improvements
===================

Add more features (e.g., recent win streak, time control type, game opening)

Try different models (Logistic Regression, Gradient Boosting, Neural Networks)

Perform hyperparameter tuning with GridSearchCV
