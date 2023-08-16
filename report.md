# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

This analysis was conducted with the intent of developing a model to predict the creditworthiness of customers. The model was intended to predict whether a customer was worthy of a loan or not. Since the outcome was binary, a logistic regression model was selected. 

The independent variables used to predict loan worthiness were:
- loan size
- interest rate
- borrower income
- debt-to-income
- number of accounts
- derogatory marks
- total debt

* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

The logistic regression model had a balanced accuracy score of 94.4%. Details of performance are below:
- **Precision**
  - Out of all the customers predicted as not worthy of a loan, 100% of those predictions were correct. 
  - Out of all the customers predicted as worthy of a loan, 87% of those predictions were correct. 
- **Recall**
  - Of all the customers who were in fact worthy of a loan, 89% of them were predicted as worthy of a loan. 
  - Of all the customers who were in fact not worthy of a loan, 100% of them were predicted as not worthy of a loan. 


## Summary

Interpretation of model performance depends on the perspective of the bank. If they are more concerned with losing money on bad loans, then this model is perfect for them, as 100% of thoes people who did not qualify for a loan were predicted as unqualified, so the bank would not have exposed itself to those risks if it followed the predictions of the model. On the other hand, if the bank is more worried about missing out on good loan opportunities, this model is likely not optimal because 11% of loan-worthy customers were not predicted as loan-worthy and thus the bank would have missed out on those opportunities. 
