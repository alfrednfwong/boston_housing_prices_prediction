﻿# boston_housing_prices_prediction


A machine learning project at Xccelerate HK, by Tiran Ranasinghe, Curtis To, Alfred Wong.

In this project we take the Boston housing prices dataset, where the target variable is the median value of owner-occupied homes in different areas in Boston, and the featrues are characteristics of the areas.

First we explore and visualize the data to look for anomalies and hopefully insights, then we do PCA and automated feature selection to generate different feature sets.

These sets of features or principal components are then fed into a gridsearch algorithm to train different classifier models. 

The gridsearch iterates lists of algorithms and hyperparameters, with a KFold cross validation each time. 

The combination of feature set, algorithm and hyperparameters with the highest R2 score is selected.


[Data source](https://raw.githubusercontent.com/scikit-learn/scikit-learn/master/sklearn/datasets/data/boston_house_prices.csv)
