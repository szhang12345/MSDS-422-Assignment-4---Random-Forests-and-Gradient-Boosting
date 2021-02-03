# MSDS-422-Assignment-4---Random-Forests-and-Gradient-Boosting
# Management Problem
Imagine that you are advising a real estate brokerage firm in its attempt to employ machine learning methods.

# Management Questions

The firm wants to use machine learning to complement conventional methods for assessing the market value of residential real estate. Of the modeling methods examined in your study, which would you recommend to management and why? Reviewing the results of the random forests and gradient boosting model you have selected to present to management, which explanatory variables are most important in predicting home prices?

# Solution Overview
This exercise builds on the linear regression models we developed for assignment 3 and uses the same data set. We drop the variable 'neighborhood' and use the remaining continuous data variables to build multiple models using SciKit Learn: Ridge, DecisionTreeRegressor, RandomForestRegressor, & GradientBoostingRegressor. By experimenting with bootstrapping and data transformation techniques (Log transform), we are able to build models that perform better than the regression models in assignment 3.
Use all explanatory variables (except neighborhood) and all 506 census tract observations from the Boston Housing Study. Use one of two response variables: (1) the median value of homes in thousands of 1970 dollars or (2) the log median value of homes in thousands of 1970 dollars. Drop the variable 'neighborhood' and use the remaining continuous data variables to build multiple models using SciKit Learn: Ridge, DecisionTreeRegressor, RandomForestRegressor, & GradientBoostingRegressor. Evaluate these methods within a cross-validation design, using root mean-squared error (RMSE) as an index of prediction error. Python scikit-learn should be your primary environment for conducting this research.
