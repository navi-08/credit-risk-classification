# credit-risk-classification
supervised learning

        ****Overview:**
The purpose of this analysis is to evaluate the performance of a logistic regression model trained with oversampled data for predicting loan categories - healthy (label `0`) and high-risk (label `1`). The oversampling is applied to address class imbalance, and the goal is to assess how well the model identifies both types of loans.

**Model Evaluation Metrics:**
- **Accuracy:** 99%
- **Precision (Label `0` - Healthy Loans):** 100%
- **Recall (Label `0` - Healthy Loans):** 99%
- **F1-score (Label `0` - Healthy Loans):** 100%
- **Precision (Label `1` - High-Risk Loans):** 84%
- **Recall (Label `1` - High-Risk Loans):** 99%
- **F1-score (Label `1` - High-Risk Loans):** 91%

**Summary:**
The logistic regression model, trained with oversampled data, demonstrates exceptional performance in predicting both healthy and high-risk loans. It achieves perfect precision and recall for healthy loans and maintains a good balance for high-risk loans. The overall accuracy stands at 99%, showcasing the model's robustness.

**Recommendation:**
- **Positive Aspects:**
  - Exceptional performance in identifying healthy loans.
  - Effective capture of high-risk loans with a good balance between precision and recall.
  - High overall accuracy and well-balanced metrics indicate model robustness.

- **Recommendation:**
  - **Recommended:** The model is recommended for use by the company due to its outstanding performance in accurately classifying both healthy and high-risk loans. The high precision and recall scores, along with a 99% accuracy, make it a reliable tool for loan categorization.

- **Justification:**
  - The model's ability to achieve a perfect F1-score for healthy loans and a well-balanced F1-score for high-risk loans demonstrates its effectiveness in addressing the company's classification needs. The high accuracy further supports its reliability, making it a suitable choice for deployment in a real-world scenario.**




                    In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Before You Begin
Create a new repository for this project called credit-risk-classification. Do not add this homework to an existing repository.

Clone the new repository to your computer.

Inside your credit-risk-classification repository, create a folder titled "Credit_Risk."

Inside the "Credit_Risk" folder, add the credit_risk_classification.ipynb and lending_data.csv files found in the "Starter_Code.zip" file.

Push your changes to GitHub.

Files
Download the following files to help you get started:

Module 20 Challenge filesLinks to an external site.
Instructions
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

NOTE
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.



