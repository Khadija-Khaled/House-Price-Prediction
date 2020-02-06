# House-Price-Prediction

This is my first project using linear regression and multiple features using python.

First, we get the correlation between the features and the dependent variables, dropping those that have low correlation as they do not affect the output much. Then we get the correlation between the features, dropping those that are highly correlated as they would provide redundant information.

The following statistics for KC housing dataset, describe the price range:

* Minimum price: $75000.0
* Maximum price: $7700000.0
* Mean price: $540088.1417665294
* Median price $450000.0
* Standard deviation of prices: $367118.7031813723

The figures displayed in the notebook show the effect of each of the highly correlated features and the price on each other and on the price.

A linear model was then created using SKlearn library with the result of RMSE = 189656.17504220724




