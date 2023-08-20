# Bike Sharing Assignment
> Objective is to build a required model that predict the Price of the house with the available independent variables. It will be used by the management to understand how the sale price vary with different features. Based on the model prediction/ demand understand, the stretegy will be manipulated to meet the demand levels and meet the customer's expectations. The most fit model will be further way for understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Analysis Involved](#analysis-involved)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
- Dataset of house properties and it's sale price details from the company
- The objective is to predict the sale price on the house and identify the variables
- train.csv (House property data)

## Technologies Used
- seaborn - version 0.12.2
- pandas - version 2.0.3
- matplotlib - version 3.7.2
- numpy - version
- statsmodels - version 0.14.0
- scikit-learn - version 1.3.0
- statsmodels - 0.14.0

## Analysis Involved
- Exploratory data analysis
- lasso regression: model_1 building and it's evaluation
- ridge regression: model_2 building and it's evaluation
- Regularization: values coeff's analysis
- GridSearchCV: alpha value finding

## Conclusions
These features are the best variables that explains the SalePrice of the house. There are still more I have listed the top 6 variables only.<br>
So, The company can focus on these variables on priority.
- LotArea
- MSZoning
- 1stFlrSF
- BsmtUnfSF
- OverallQual
- LowQualFinSF
Best Alpha values:
- Ridge: 1.0
- Lasso: 0.001

## Contact
Created by [@rgurum](https://www.linkedin.com/in/gurumoorthiramanathan/) - feel free to contact me!
