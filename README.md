# Advanced Regression Assignment 

Using an advanced regression model, we are trying to identify variables that are significant in predicting house prices, and how well they describe house prices.


General Information
The US-based housing company Surprise Housing has decided to enter the Australian market. Using data analytics, the company purchases houses below their actual values and flips them for a profit. The company has also collected data on Australian house sales for the same purpose. 

In order to enter the market, the company is looking at prospective properties to buy. To determine whether to invest in the prospective properties, you must build a regression model using regularisation.

Specifically, the company is interested in: • Which variables are significant in predicting house prices, and • How well these variables describe house prices.

Determine the optimal lambda value for ridge and lasso regressions


Conclusions
In my opinion, Lasso Regression is better than Ridge Regression.

When compared to Ridge Regression, Lasso Regression has slightly better R2 Score, RSS, and MSE values
By using Lasso Regression, we can push model coefficients to zero. In other words, features with co-efficents of 0 can be removed from the model. This results in the selection of features
We can also reduce the complexity of the model by removing features with zero coefficients.
In terms of predictor features, OverallQual is among the top 10,LotArea, GarageCars,YearBuild,fireplaces,OverallCond,HouseStyle_2.5Fin,Neighborhood_Crawfor,YearRemodAdd and MSZoning_RH
