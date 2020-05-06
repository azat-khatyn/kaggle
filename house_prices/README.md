### House Prices: Advanced Regression Technique Challenge

This notebook contains a solution for the House Prices Challenge. https://www.kaggle.com/c/house-prices-advanced-regression-techniques

#### About the challenge:

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Practice Skills Creative feature engineering Advanced regression techniques like random forest and gradient boosting

#### About this notebook:

This notebook starts with Data Preprocessing (handling target feature values,
performing feature engineering, whearres some transformations will be performed on merged train and test datasets and others separately to avoid data leakage;
handle outliers).

The modelling part of the notebook contains checking baseline single models (Lasso and Ridge Regressions, XGboost and LightGBM, ElasticNet, Support Vector Regression) as well as stack modelling, taking a weighted sum of predictions from different models and attaining and evaluating the final result

#### About the results:

The final predictions, produced by the blended model scored 0.18324, which corresponds to top 5% on the public leaderboard.