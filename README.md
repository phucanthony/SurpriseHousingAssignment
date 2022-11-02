# Surprise Housing Assignment
> Building a Linear Regression model with the help of Ridge and Lasso Regularization Method to identify the significant variables in predicting the housing price


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
This is an assignment in which we use Python to build a Linear Regression model to understand Surprise Housing - a US-based housing company.

In this project, we need to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.

We use the `train.csv` (included in this repository) to build the model.

## Conclusions
Those are the conclusions retrieved from the model, further information can be found in the Notebook

After our final model, we can conclude from the top predictor variables
- `OverallCond` (Overall condition of the house): `Fair` condition will result in a reduce in house price by 14%
- `OverallQual` (Overal material and finish of the house) highly affects the price of the house, `Very Good` and `Excellent` condition can increase house price from 1.08 to 1.17 times
- `CentralAir_Y` (Central air conditioning): If the house has a centralized air conditioning system, the price will increase by 1.12 times
- `Neighborhood_Crawfor`, `Neighborhood_Somerst`, `Neighborhood_StoneBr`: If the house is located within Crawford, Somerset and Stone Brook the housing price can go up from 7% to 11%
- `GrLivArea`: One foot of area above the ground will result in 1.11 times increase in the price of the house
- `SaleType_New`: Houses that were just constructed and sold will be 1.07 times higher in price than the others


## Technologies Used
- `python` - version 3.9
- `pandas` - version 1.4.3
- `numpy` - version 1.23.0
- `notebook` - version 6.4.12
- `matplotlib` - version 3.5.2
- `seaborn` - version 0.11.2
- `scikit-learn` - version 1.1.2
- `statsmodels` - version 0.13.2

## Contact
Created by [@phucanthony] - feel free to contact me!

