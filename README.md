# Titanic: Machine Learning from Disaster

## Overview

This project is based on the [Kaggle Titanic Challenge](https://www.kaggle.com/c/titanic). In this competition the participants were asked to analyze data and apply machine learning to predict which passengers survived the tragedy.

## Data

Participants were provided with the following data about passengers:

* PassengerId: Type should be integers
* Survived: Survived or Not
* Pclass: Class of Travel
* Name: Name of Passenger
* Sex: Gender
* Age
* SibSp: Number of Sibling/Spouse abord
* Parch: Number of Parent/Child abord
* Ticket
* Fare
* Cabin
* Embarked: The port in which a passenger has embarked. C - Cherbourg, S - Southampton, Q - Queenstown

## Objective

Predict the column "Survived", that indicates if a passenger survived the tragedy (1) or not (0), based on the other columns of the dataset.

## Metric

The evaluation is made by using the accuracy metric, which indicates the percentage of passengers correctly classified as survived or not survived. 

## Steps

* [Exploratory data analysis](https://github.com/amandinhame/kaggle-titanic/blob/master/exploratory-data-analysis.ipynb)
* [Data preparation](https://github.com/amandinhame/kaggle-titanic/blob/master/data-preparation.ipynb)
* [Modeling and Validation](https://github.com/amandinhame/kaggle-titanic/blob/master/modeling-evaluation.ipynb)