# Housing Sale Price Prediction
> Have build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info]
* [Procedure]
* [Conclusions]



## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The company is looking at prospective properties to buy to enter the market. 
- Required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.
- The data is provided in the train.CSV file

## Procedure
- Data reading and understanding
- Data Cleaning using median and removing colums with more than 17% missing values
- EDA
- Removing redundant variables
- Train-Test Split
- Feture selection using RFE
- residual analysis
- Ridge Regression
- Lasso Regression
- Model coefficient comparison
- Final model

## Conclusions

- Optimum alpha = 50 for ridge and 0.01 for lasso model.
- Ridge Regression is chosen as final model for having slightly better R-square value
- Out of 40 features in the final model, top 10 features in order of descending importance are 'OverallQual', 'GrLivArea', '1stFlrSF', 'Fireplaces', '2ndFlrSF','FullBath', 'GarageArea', 'KitchenQual', 'BsmtFinSF1', 'ExterQual'






