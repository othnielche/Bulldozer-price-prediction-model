# Bulldozer-price-prediction-model

# Predicting the Sale Price of Bulldozers using Machine Learning 

In this notebook, I am going to go through a machine learning project with the goal with of predicting the sale proce of bulldozers.

## 1. Problem Definition 

> How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for 
## 2. Data 

The data is downloaded from the Kaggle Bluebook for Bulldozers competition:

https://www.kaggle.com/c/bluebook-for-bulldozers/data
There are 3 main datasets:

* Train.csv is the training set, which contains data through the end of 2011.

* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competetion.

## 3. Evaluation

The evaluation metric for this project will be the RMSLE (root mean squared log erro) between the actual and predicted auction prices.

For more on the evaluation of this project check:
https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

The goal for this project is to build a model which minimises the RMSLE.

## 4. Features

kaggle provides a data dictionary detailing all the features of the data set:
https://docs.google.com/spreadsheets/d/1bws9wk7fCS2K6HTJzomYpazqk12XrxYwukh49iiaYQc/edit?usp=sharing
