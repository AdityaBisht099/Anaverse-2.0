Anomaly Detection on Sensor Data
Description

This project focuses on detecting anomalies in sensor readings using supervised machine learning. The dataset is highly imbalanced, with anomalies occurring very rarely, so the model is evaluated using F1 score instead of accuracy.

This project was built as part of the Celebal AnaVerse 2.0 Data Science Hiring Challenge.

Problem Statement

Given time-stamped sensor data, predict whether each record represents:

0 → Normal behavior

1 → Anomalous behavior

Approach

Performed basic data analysis and preprocessing

Extracted time-based features (year, month, day) from the date column

Handled class imbalance using class-weighted learning

Trained multiple models and selected Random Forest based on F1 score

Generated predictions for unseen test data

Tech Stack

Python

Pandas, NumPy

Scikit-learn

Jupyter Notebook

Result

Rank: 91 / 1090

Leaderboard: Top ~9%

Files
notebook.ipynb   - Model training and evaluation
submission.csv  - Final prediction file
