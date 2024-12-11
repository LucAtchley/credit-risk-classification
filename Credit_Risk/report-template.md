# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

In this analysis, I used a machine learning model to evaluate the creditworthiness of borrowers from a lending company. The data consisted of values such as loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt. These values were used as the X variables to be compared to the y variable. The y variable is based on the column 'loan_status'. The values in this columns were either 0(healthy loan), or 1(high-risk loan). 

I used a logistic regression model to evaluate the X data in order to predict the y data. I then used the prediction and y_test data to create a confusion matrix and classification report. These evaluated how accurate the model is at predicting creditworthiness based on the original data.


## Results


Machine Learning Model 1:
    Accuracy: The accuracy score of the model was 0.99. I beleive this is not telling the whole story, because the model's predicted healthy loans far more accurately than high-risk loans. Because the data had so many more healthy loans, the model seems a lot more accurate than it actually is. 

    Precision: The precision for healthy loans is 1, which is incredibly accurate. The score for high-risk loans is much lower at 0.85. 

    Recall: The recall score is 0.99 for 0, and 0.95 for 1. This indicates that the model is effective at predicting positive instances and minimizing false negatives.

## Summary

In my opinion, I am not really sure whether to recommend this model or not. I do not believe there is enough data on high-risk loans for the model to make a prediction regarding high-risk loans. The model had over 18,000 rows of data to analyze regarding healthy loans, but only around 600 for high-risk loans. This model did prove to be incredably accurate at predicting healthy loans, so I would like to see it work with more high-risk loan data before making a decision.


