# Prediction using Decision Boundaries with Multinomial Logistic Regression to Iris Dataset

#### -- Project Status: Completed

## Project Objective
Given a dataset with data on the size of the sepals (petals) and the size of the petals (corolla) of 150 irises consisting of three species, namely Iris setosa, Iris versicolor, and Iris virginica. Petal size will be used as a measure of flower classification using multinomial logistic regression.

### Methods Used
* Multinomial Logistic Regression

### Language
* Python

### Module
* skicit-learn
* matplotlib
* pandas
* numpy

## Step-by-step
1. Change the target variable to int to facilitate where data processing
   * 0 : Iris Setosa
   * 1 : Iris Versicolor
   * 2 : Iris Virginica
2. Take the petal size column as X data and the flower species column in the code as Y
3. Divide into training and testing data with a ratio of 3:7
4. Find the best parameter values with hypertuning for the Multinomial Logistic Regression model
5. Create a multinomial Logistic Regression model into the MLR variable
6. Predict the X test data using the MLR model
7. Obtained an accuracy report of 0.98 so that this model has a fairly high accuracy
8. Do plotting boundaries decisions
9. Make predictions with the data in the problem

## Getting Started
1. You can access the raw data [here](https://github.com/angelpatriciads/iris-data-multi-logistic-regression/blob/main/iris_dataset.csv) within this repo.
2. All of the scripts are being kept [here](https://github.com/angelpatriciads/iris-data-multi-logistic-regression/blob/main/iris_data_multi_logistic_regression.ipynb).
