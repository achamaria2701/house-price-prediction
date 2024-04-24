# House Price Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. It is required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
- This is a problem solving excercise using ridge and lasso regression technique
- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.
- The dataset contains 79 features with more than 1400 houses and the SalePrice


## Conclusions
- For ridge regression the alpha value comes out to be 10
- For lasso regression the alpha value comes out t0 be 500
- Five most important features using Lasso regression are:
    - GrLivArea: Above grade (ground) living area square feet
    - OverallQual_9: Overall material and finish of the house is “Excellent (9)” or not
    - OverallQual_10: Overall material and finish of the house is “Very Excellent (10)” or not
    - GarageCars: Size of garage in car capacity
    - Neighborhood_NoRidge: Whether the house is in Northridge or not
- R2-score using Lasso regression for train dataset is 84.59% and for test dataset is 82.66%

## Contact
Created by [@achamaria2701] - feel free to contact me!
