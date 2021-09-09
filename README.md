# House_Price_Prediction
Creating a Machine Learning Model to predict the price of different properties! 🏠

In this project we take a [Properati](https://www.properati.com.ar/ "Properati") dataset, this company is one of the biggest real state agencies in Argentina. To make a good ML Model, we need to work with good data quality, if data isn't good, probably our ML Model is going to be bad too. This dataset, particullary (not by coincidence) is a pleny of mesy data, null values, no meaningfull features, and duplicated values, we need to take care of this problem. (Keep calm I've gotcha ;) )

After that we're going to jump into the ML Model, for this task we're going to apply cross-validation to the dataset and use Multiple Regression Model, Lasso and Ridge Regresions, Random Forest Model, and XG Boosting Model. 

## 1. Perform EDA (exploratory data analysis) and Data Wrangling

This dataset it has extremely mesy data, null values, no meaningfull features, and duplicated values. 

Our first attempt is clear the data, make an EDA (exploratory data analysis), perform a consistent data wrangling, create new meaningfull features wich can be usefull for the Machine Learning Model. This ML Model is going to predict the price of the new upcoming propertie based on the data that we already have.   

## 2. Building the Machine Learning Model

Let's see... in this part of the project, we have to split the dataset in train (70%) and test (30%) with cross-validation. Once we have that, our first mission is run a Multiple Regression model and evaluate the metrics, this would be our base model. We need to understand the metrics (R2, R2 adjusted, RMSE, and MAE). Taking this as a starting poin, we start our job as ML Engineers, we need to improve the metrics and achive the best results that we can!   

Check the code in the notebooks bellow! 😉👇🏻
