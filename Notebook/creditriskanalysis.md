# Credit Risk Analysis

## Overview of the Analysis
The purpose of the credit risk analysis is to assist with predictions on whether a loan borrower is low-risk or high-risk. Low-risk applicants are categorized as healthy loans, high-risk as high-risk. The selected method to determine total value/number predictions was a logistic regression model based on loan borrower's income and financial loan information such as size and interest rate. To start off, the model was established using classification of variables. Then using best practices, was trained, tested and split into training and test datasets for analysis. Once established, predictions were run on the model and provided confusion metrix in order to assess the accuracy, precision and recall score of the model.

## Results
The model provided a high overall accuracy score of 0.99, indicating 99% of the time the model predicts loan risk accurately. It is most accurate when predicting healthy loan borrower's, and may become more accurate with additional data used in further predictions or building out the training set. The model support for healthy loans was 18,765 while it was 619 for high-risk loans.

* Healthy Loan Model Results:
    * Precision: 1.00
    * Recall: 0.99
    * F1-Score: 1.00
 
* High-Risk Loan Model Results
    * Precision: 0.85
    * Recall: 0.91
    * F1-Score: 0.88
 
## Summary
The logistic regression model has strong performance in predicting loan risk. With an overall accuracy score of 0.99, the model shows a high level of reliability, correctly classifying loan risk 99% of the time. The model is highly effective at identifying healthy loans with a low rate of false positives. For high-risk loans, the model is good/okay at predicting high-risk loans, less accurate compared to healthy loans, with some trade-offs between precision and recall.

Overall, the model performs exceptionally well in predicting healthy loans but could be improved identifying high-risk loans. This discrepancy may be due to class imbalance, where there are significantly more healthy loans compared to high-risk loans in the dataset.

Since predicting high-risk loans is critical and greater cause for concern/loss to lenders, I would not recommend utilizing this model without further training to enhance the accuracy for high-risk loan preictions. To address the class imbalance and improve high-risk loan prediction, alternative models and feature engineering (adding more features) could be explored.




