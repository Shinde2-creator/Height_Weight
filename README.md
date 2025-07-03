# Title - Height_Weight
Took the dataset from Kaggle and used linear regression with MSE evaluation to get the result.


## Problem Overview

In this project we will use linear regression to predict weight from height, age, and activity level. This type of predictive modelling can be helpful for health care practitioners’ knowledge of patient risk factors and providing more tailored advice on one’s health.

## Approach

The data used in this study came from a Kaggle dataset ("Weight-Height") and the age/activity level were simulated for the purposes of this demonstration. 
- Data pre-processing used ordinal encoding for the categorical variable activity level and then relevant features were selected. 
- Linear Regression was explored as the supervised learning algorithm.

## Evaluation

Model evaluation was accomplished using mean squared error (MSE), a common metric expressing prediction error in regression. 
- The prediction weight values will be near the actual values, the MSE will produce lower values.

## Reflection

This simplistic regression model demonstrated how basic health indicators can be applied to a regression applied to a health care context. In a real-world situation, one would be able to collect actual age and activity level data and using more sophisticated models can increase predicting accuracy.
