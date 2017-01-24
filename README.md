### Store Model


This is an analysis of the daily unit sales of 39 products at 181 convenience stores over nine months. The end result is a linear regression based prediction model utilizing the [Stochastic Gradient Descent Regressor](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.SGDRegressor.html) from sckit-learn.

The data is prepared utiling [pandas](http://pandas.pydata.org/) to calculate average trailing sales for unequal intra-week periods.

Predictions for each item for each store for each period are delivered in a multi-level pivot table.
