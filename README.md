# credit-risk-classification

## The purpose of Analysis

By utilizing a dataset of historical lending activity from a peer-to-peer lending services company, we aim to create a model capable of accurately assessing the creditworthiness of borrowers. The purpose of this analysis is to develop a model that can identify applicants as either 'healthy loan' or 'high-risk loan' based on essential application factors. These factors encompass loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. Then we will evaluate the effectiveness of the model.


## The results

Accuracy: 99%
Precision for 'healthy loans': 100%
Precision for 'high risk loans': 85%
Recall for 'healthy loans': 99%
Recall for 'high risk loans': 91%


## Summary

The Logistic Regression model exhibits excellent performance in predicting healthy loans, achieving accuracy, precision, and recall rates close to 100%. However, its performance slightly declines when identifying high-risk loans, where precision stands at 85% and recall at 91%. This discrepancy indicates that the model is comparatively less proficient in classifying high-risk loans compared to healthy loans. Thus, I don't recommend this model for use as it may lead to financial losses for the company.