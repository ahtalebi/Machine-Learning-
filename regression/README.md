![LR](https://github.com/ahtalebi/Machine-Learning-/blob/5b0cd39520726b19c25d77565e07106ef5a34d2b/images/LR1.png)


# Predicting Residential Property Prices with Regression

Predicting the selling price of a residential property depends on various factors such as property age, local services, and location. This folder utilizes regression techniques to analyze a dataset of real estate sales transactions and predict the price-per-unit of a property based on given features.

## Data Source

The dataset used in this project is sourced from the following study:

**Title:** Building real estate valuation models with comparative approach through case-based reasoning  
**Authors:** Yeh, I. C., & Hsu, T. K.  
**Publication:** Applied Soft Computing, 65, 260-271 (2018)

and can be found in the [UCI Machine Learning Repository](https://archive.ics.uci.edu/).

## Description

In our analysis, we explored two regression models: Linear Regression, Random Forest and Neural Network. Random Forest showed a slightly lower RMSE, closer to 7, compared to Linear Regression.

As a result, we decided to proceed with the Random Forest model for prediction. To improve its performance, we made the following adjustments:

- Increasing the size of the training data to 80% instead of 70%.
- Increasing the number of decision trees (n_estimators) to 80.

It's worth noting that, to achieve an RMSE less than 7, we did not remove outliers from the dataset.
