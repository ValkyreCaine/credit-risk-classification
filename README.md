## Overview of the Analysis

This analysis evaluates a machine learning model for credit risk classifications. Our data set includes financial information necessary to make predictions about loan applicants. Our goal is to predict whether a loan is high or low risk based on these features. The model is designed to be used by financial institutions to aide in the lending process by identifying potentially high risk loans.  

## Process

1. Data Preparation:
   *Loaded the dataset into a pandas dataframe
   *Isolated the target variable of loan_status away from the remaining features
2. Model:
   *Applied a Logistic Regression model for the classification and predictions
3. Evaluation:
   *Assessed the performance of the model using a confusion matrix and classification report

## Results

* Logistic Regression Model:
  * Accuracy: 99%
      * Class 1:
         * Precision: 87% 
         * Recall: 95%
         * F1-Score: 91%
      * Class 0:
         * Precision: 100% 
         * Recall: 100%
         * F1-Score: 100%

## Summary

This logistic regression model performs exceptionally well at predicting loans. The accuracy score of 99% provides high levels of confidence in the models ability. Considering the subject matter, recall is increasingly important as it ensures we are correctly identifying as many high-risk loans as possible. The 95% accurate recall score of high risk loans lends this model to be a viable option for credit based risk assessment, though it should be used in combination with other factors. 
