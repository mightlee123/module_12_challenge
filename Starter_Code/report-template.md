# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    Build a model that finds a good borrower.
* Explain what financial information the data was on, and what you needed to predict.
    loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, and total_debt
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
    0s are the healthy loans, 1s are the high-risk loans 
* Describe the stages of the machine learning process you went through as part of this analysis.
    Split data in to X and y; Split data to training and testing; Use the logistic regression model. 
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  Accuracy: 95%
  Precision: healthy loans = 1 , high-risk loans = .85
  Recall: 91% of loans are high-risk loans 


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  Accuracy: 99%
  Precision: healthy loans = 1 , high-risk loans = .84
  Recall: 99% of loans are high-risk loans 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

model 2 is recommended over model 1, because it yelds a higher accuracy with oversampled data. 