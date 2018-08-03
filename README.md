# regressions
Examples of different machine learning regression models

## This repository contains example implementations of some common regression models:
+ Simple Linear Regression
+ Multiple Linear Regression
+ Polynomial Regression
+ Support Vector for Regression (SVR)
+ Decision Tree Classification
+ Random Forest Classification

These models are suitable for determining real values in *prediction* scenarios, where we could be forecasting a future value in a time series, or trying to prdict an unknown value based on some observations.

### A note on evaluating these models:
The models contained in these notebooks are just demosntrations of the machine learning models in Python, not full blown analyses. There are some important, citical, steps left out for these to be meaningful as a data product. Of the important things left out, one that directly pertains to these models in the evaluation step of the model's performance.

For regression models, it is worth considering the $R^{2}$ or the adjusted $R^{2}$ when evaluating their performance. Also, consider interpreting your model's coefficients when telling the story. These represent the unit increase, or decrease, for whatever field they are describing in your model.
