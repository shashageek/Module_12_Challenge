# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to identify creditworthiness of borroowers and predict risky loans using financial features.

* The loan status, "0" for healthy and "1" for risky is what this analysis needs to predict, and financial information (features) include loan size, interest rate, borrower income, debt to income ratio, number of debt accounts, derogatory, and total debt.

* In the dataset, the loan status has 75036 of "0" (healthy loans) and 2500 of "1" (risky loans).

* Stages of the Machine Learning process are model, fit, and predict.

* Methods used are `LogisticRegression` for prediction model and `RandomOverSampler` to oversample the data. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Model 1 accuracy is 95.20%, Precision is 99.70%, Recall is 99.46%.

* Machine Learning Model 2:
  * Model 2 accuracy is 99.37%, Precision is 99.98%, Recall is 99.38%.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? Model 2 performs better than Model 1 as its precision score is higher and is more accurate to predict risky loans than Model 1. 
* The preformace depends on the objective of the analysis. As we are trying to predict risky loans, accuracy of predicting "1" is more important than predicting "0".

If you do not recommend any of the models, please justify your reasoning.
