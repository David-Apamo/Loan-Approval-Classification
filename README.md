# Loan-Approval-Classification

This repository contains analysis files for Loan Approval Classification project using Machine Learning. The data for this project is an open source data found on Kaggle. The data has various attributes like loan ID, loan amount, loan amount term, credit history, applicant’s income, co-applicant income, property area, loan amount term, education, number of dependents, marital status, self employment and loan status. In the highly competitive and risk-laden field of finance, ensuring the reliability of loan approvals is paramount for banks and financial institutions. The proliferation of bad loans can significantly impact the financial stability and profitability of these institutions. To address this challenge, my aim was to develop a robust classification model aimed at predicting loan approval outcomes with high accuracy, using advanced machine learning techniques.

## Models Used:
* Logistic Regression
* Naive Bayes Classifier
* K-Nearest Neighbors (KNN)
* Random Forest (RF)
* SVM
* XGBoost

After tuning and evaluating the models, **RSVM and XGBoost** achieved the best performance, both with an **accuracy of 82.79%**. However, **SVM** had the best **Precision and Specificity** of **100%** each. The SVM model is very good at identifying/detecting customers who do not qualify for loans.

## Key Processes

* **Data Preprocessing:** Cleaning and preprocessing the data to handle missing values, normalize features, and encode categorical variables.
* **EDA:** Summarizing the data to obtain measures of centrality, and visualizing the data to gain insights and understand existing patterns.
* **Feature Engineering:** Data partitioning, feature selection, feature normalization, label encoding categorical features.
* **Model Selection:** Exploring and selecting the appropriate classification algorithms such as Logistic Regression, Random Forest, Gradient Boosting, etc.
* **Model Training:** Using the preprocessed dataset to train and fine-tune the model parameters with Cross-validation to optimize performance.
* **Model Evaluation:** Evaluating the model performance using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.

## Tools and Libraries
RStudio (tidyverse, janitor, caret, mlr, tidymodels, VIM, parallel, parallelMap, pROC, vip, corrplot)

## Model Application

The model will be useful for Banks and money lending companies, as it will help them to identify customers who do not qualify for loans and prevent them from issuing bad loans, hence reducing losses incurred from loan defaults.

## Contributions
Contributions to improve the model performance and reliability are welcome. Please fork the repository, make your changes, and submit a pull request.
