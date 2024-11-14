# credit-risk-classification
Machine learning techniques are used to analyze a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis

Factors considered in the analysis included data on:

* the size of the loan
* its interest rate
* the borrower's income
* the debt to income ratio
* the number of accounts the borrower held
* derogatory marks against the borrower
* the total debt
The dataset (77,536 data points) was split into training and testing sets. The training set was used to build an initial logistic regression model (Logistic Regression Model) using the LogisticRegression module from scikit-learn. Logistic Regression Model  was then applied to the testing dataset. The purpose of the model was to determine whether a loan to the borrower in the testing set would be low- or high-risk .
This intial model was drawing from a dataset that had 75,036 low-risk loan data points and 2,500 high-risk data points.The resampled data was used to build a logistic regression model. The purpose of Logistic Regression Model was to determine whether a loan to the borrower in the testing set would be low- or high-risk. The results are summarized below.

## Results

Logistic Regression Model:

 * Precision: 93% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
 * Accuracy: 94%
 * Recall: 95% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)

## Summary

The Logistic Regression model demonstrates strong overall performance with an accuracy of 94%. It shows exceptional precision in predicting low-risk loans at 100%, but slightly lower precision for high-risk loans at 87%, leading to an average precision of 93%. In terms of recall, the model again excels with a perfect recall of 100% for low-risk loans, while achieving a recall of 89% for high-risk loans, resulting in an average recall of 95%.

Overall, the model is highly effective, particularly in identifying low-risk loans, although there is room for improvement in predicting high-risk loans. This analysis highlights the model's strengths and areas for potential enhancement in its predictive capabilities.
