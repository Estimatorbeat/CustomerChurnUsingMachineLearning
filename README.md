# CustomerChurnUsingMachineLearning

![image](https://github.com/Estimatorbeat/CustomerChurnUsingMachineLearning/assets/154437491/3a549df4-749d-447a-aca4-c60abe932a79)

## Project Overview
The "Customer Churn using Marchine Learning' project aims aims to develop a robust customer churn prediction systems. By leveraging advanced analytics and machine
learning techniques on available customer data, to accurately forecast customer churn and implement targeted retention initiatives

## Project Objective
The primary objective of this project is to build and train a robust machine learning model that can accurately detect if customer churn. The model will be designed to accurately predict customer churn

## Data Sources
The dataset used in this project was provided by 10Alytics. The data set contains customer demprographic including gender, senior citizen, partner and other relevant information

## Data Preprocessing 
Before feeding the data into the machine learning model, extensive data processing was performed. This include handling missing value, encoding categorical variables, scaling features. Additionally, feature engineering techniques were applied to extract relevant information from the data

## Machine Learning Model
The churn prediction model is built using a supervised marchine learning approach. Training and test data was spilt 80:20. Several classification algorithm were experimented with such as:

- **Decisipon Trees
- **Random Forest
- **Logistic Regression

After Extensive experimentation and tuning, the final machine learning was selected based on its performance and generalization capabilities.

## Evaluation Metrics
To assess the performance of the machine learniung model, the following evaluation metrics were used:

- **Precision:** The proportion of correctly identified customer churn among all customer classified as churn.
- **Recall:** The proportion of correctly identified customer churn among all actual customer classified as churn.
- **F1-score:** The harmonic mean of precision and recall, providing a balance metric for model evaluation.
- **Accuracy:** Accuracy measures the overall correctness of the model's predictions.(both churn and non-churn).

## Key Insights
- The purpose of this project is to aims to develop a robust customer churn prediction system.
- The best model that predicts with less error is to be chosen, subjecting them to the diiferent metrics including k-foldcross validation(accuracy, precision and recall).
- The confusion matrix displays the error value for each model in terms of False Positive (Where the model predicts a customer churn when they actually didn't churn - Precision) and False Negative (Where the model predicts a customer didn't churn where they actually churn - Recall).
- After Cross Validation, the model with the highest recall will be deployed. Recall  is the most relevant matrix for evaluation in this business problem. This is because, the effort of the error (Recall) on the business if not addressed will be massive compared to that of precision


## Conclusion
The 'Customer Churn using Marchine Learning' project showcases the effectiveness of machinee learning algorithms in prediciting customer churn activities. By accurately identifying and predicting customer churn, this model enhances personalized churn predictions for individual customers based on their unique characteristics, behaviors, and interactions with the telecom company.
LogisticRegression: For this business problem, Recall score is of more relevant and LogisticRegression has highest recall score compared to other models. hence, It should be depolyed by ConnectTel Telecom Company for faceing the pressing need to address customer churn, as it has 74% Recall and Accuracy is 89%.
