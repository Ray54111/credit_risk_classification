## Overview of the Analysis


The goal for bank stakeholders is to create a machine learning model to accurately predict if a loan application is high risk. Using data of applicants as features to determine the label of high-risk, a linear regression model was used. The Supervised Machine Learning method was used since we are able to note the features and determine an outcome. The variables used can be seen listed below. 


The variables used:
loan size,
interest rate,
borrower income,
debt to income,
num of accounts,
derogatory marks,
total debt,
loan status

Data Size:
77536 rows x 8 columns

As with other types of Machine Learning, the model was begun to preprocessing the data into to variables, X and y. Then those variables were split into a 
testing and training group. Afterwards, the training data was fitted and predictions were made by the testing group using the trained model. Once we had 
the results of the prediction are compared to the actual outcome of the loan and scored.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Linear Regression model:

Healthy Loan Scores:
   *  precision 1.00      
   * recall 0.99      
   * fi-score 1.00     
   * Support 18765

Risky Loan:
  *precision 0.85
  *recall 0.91
  *fi-score 0.88
  *recall 619



* Resampled model:

Healthy Loan Scores:
   *  precision 1.00      
   * recall 0.99      
   * fi-score 1.00     
   * Support 18765

Risky Loan:
  *precision 0.84
  *recall 0.94
  *fi-score 0.91
  *recall 619

## Summary

From the models both provide a high accuracy for a healthy loan. This can alter the question lenders may ask to see if the applicant can provide a healthy 
loan instead of ask if they are a high risk applicant. Since there is much more data on healthy loans and great accuracy healthy loans should be focused. 
The at risk model results provide high enough accuracy, but there still needs more data to build the accuracy of the model.
