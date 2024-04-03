Machine Learning Model Performance Analysis

Overview of the Analysis
The purpose of this analysis is to evaluate the performance of machine learning models trained on loan data to predict whether a loan is healthy or high-risk. The models are evaluated based on their accuracy, precision, recall, and confusion matrix scores to determine their effectiveness in classifying loans.

Results
Logistic Regression Model:

Accuracy Score: 0.99
Precision Score (Healthy Loans): 1.00
Precision Score (High-Risk Loans): 0.85
Recall Score (Healthy Loans): 0.99
Recall Score (High-Risk Loans): 0.91
Confusion Matrix (Logistic Regression Model): [[18663, 102], [56, 563]]

This indicates:

18663 instances were correctly predicted as healthy loans (True Negatives).
102 instances were incorrectly predicted as high-risk loans (False Positives).
56 instances were incorrectly predicted as healthy loans (False Negatives).
563 instances were correctly predicted as high-risk loans (True Positives).
Summary
The logistic regression model demonstrates high accuracy in predicting both healthy and high-risk loans, with an accuracy score of 0.99. For healthy loans, the model achieves perfect precision and high recall, indicating that it correctly identifies almost all actual healthy loans while minimizing false positives. For high-risk loans, the model achieves a precision score of 0.85 and a recall score of 0.91, indicating a good balance between precision and recall, although there are some false positives.

Based on these results, the logistic regression model is recommended for use by the company. It demonstrates excellent performance in accurately classifying loans, particularly healthy loans. While there are some false positives in predicting high-risk loans, the overall performance of the model is satisfactory and can provide valuable insights for the company's loan approval process.
