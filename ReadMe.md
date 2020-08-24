# Risky Business

In this project we will be testing various sampling methods as well as ensamble methods. 

The first notebook found here: [credit_risk_resampling.ipynb](credit_risk_resampling.ipynb)

In this notebook we are looking at an inbalanced dataset and determining if Oversampling/undersampling/combined methods are better than no adjusmtne at all.
Based on our findings we colclude the following:

### Which model had the best balanced accuracy score?
    * SMOTE oversampling has a slightly better score than SMOTEEN Combined
### Which model had the best recall score?
    * Both SMOTE oversampling and SMOTEEN Combined sampling have the same recall score
### Which model had the best geometric mean score?
    * Both Oversampling method and the combined method have the same and highest geometric mean


The second notebook found here: [credit_risk_ensemble.ipynb](credit_risk_ensemble.ipynb)

In this notebook we are looking at an inbalanced dataset and determining which ensamble method leads to better results
Based on our findings we colclude the following:

### Which model had the best balanced accuracy score?
    * The adaBoost Classifier had the best accuracy score
### Which model had the best recall score?
    * The adaBoost Classifier also had the best recall score
### Which model had the best geometric mean score?
    * The best geometric mean was also the adaBoost Classifier
### What are the top three features?
    * the top three featiures are borrower's income, interest rates, debt to income