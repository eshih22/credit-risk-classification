# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of the analysis was to develop a predictive model to assess the risk associated with loans based on financial information. 

The dataset contained various financial attributes related to loan applications, such as borrower information, credit scores, income, loan amounts, loan terms, and loan status (healthy or high-risk).

Stages of the Machine Learning Process:

1. Data Preparation: Reading the CSV file, separating features and target variable, and splitting the data into training and testing sets.
2. Model Selection: Choosing Logistic Regression as the classification algorithm.
3. Model Training: Fitting the Logistic Regression model on the training data.
4. Model Evaluation: Making predictions on the test data, generating a confusion matrix, and printing a classification report to evaluate model performance.

The primary method used in this analysis is Logistic Regression, which is instantiated and trained using the LogisticRegression class from scikit-learn. Additionally, the train_test_split function from scikit-learn is used for data splitting, and evaluation metrics such as confusion matrix and classification report are utilized to assess model performance.


## Results

*Logistic Regression Model:
    * Accuracy Score: The accuracy score is 0.99, indicating that 99% of the predictions made by the model are correct.
    *Precision Score:
        *Precision for label 0 (healthy loan): Precision is 1.00, meaning that all predictions labeled as healthy loans are indeed healthy.
        *Precision for label 1 (high-risk loan): Precision is 0.85, indicating that 85% of the predicted high-risk loans are correctly classified.
*Recall Score:
    *Recall for label 0 (healthy loan): Recall is 0.99, indicating that the model correctly identifies 99% of the actual healthy loans.
    *Recall for label 1 (high-risk loan): Recall is 0.91, suggesting that the model captures 91% of the actual high-risk loans.


## Summary

The Logistic Regression model achieved high performance in predicting both healthy (label 0) and high-risk loans (label 1). It demonstrated an accuracy score of 0.99, indicating that 99% of the predictions were correct.