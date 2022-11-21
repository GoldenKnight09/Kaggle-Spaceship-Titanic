# Kaggle-Spaceship-Titanic

This repository contains analysis of the Spaceship Titanic disaster from Kaggle. This dataset represents a hypothetical event based on the actual historical Titanic. It is still essentially a classification problem, although in this case some of the passengers have been transported to another dimension. The dataset is part of a [sample competition](https://www.kaggle.com/competitions/spaceship-titanic) with a leaderboard for scoring submissions based on classification accuracy.

(One drawback from classifying a portion of the data from the original Titanic disaster was that since it was a historic event there were records which allowed for determination with perfect accuracy which passengers survived and which did not.)

### Contents (each part consists of a Jupyter Notebook using a Python kernel):
- [Exploratory Data Analysis](https://github.com/GoldenKnight09/Kaggle-Spaceship-Titanic/blob/main/Exploratory%20Data%20Analysis.ipynb)
- [Feature Imputation & Encoding](https://github.com/GoldenKnight09/Kaggle-Spaceship-Titanic/blob/main/Feature%20Imputation%20%26%20Encoding.ipynb)
- Machine Learning Analysis

## Key Learnings:
Data analysis suggested the features that influenced whether a passenger was transported included:
- Passenger home planet (and to a lesser extent, destination)
- Whether or not the passenger was in cryosleep
- The deck the passenger's cabin was located on
- Passenger age
- Passenger expenditures
  
The data analysis did not however, reveal how significantly each feature influenced the response. However, based on intuition, it is plausible that cabin location (e.g. cabin deck) should be a key feature (as it was in the original Titanic disaster). With this in mind, many of the features in the above list may be indicative or correlated with cabin location (for example, the passenger's home planet greatly influenced which deck the passenger cabin would be on).
