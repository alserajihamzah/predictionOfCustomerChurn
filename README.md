Predicting Customer Churn Using Data Analysis and Machine Learning
Project Overview

This project focuses on predicting customer churn using data analysis and machine learning techniques. Customer churn refers to the phenomenon where customers discontinue their service or subscription. Predicting churn is a relevant real-world problem, especially for companies operating with subscription-based business models such as telecommunications providers.

The project analyzes customer data and compares the performance of two classification algorithms:

Logistic Regression

Decision Tree

The goal is to determine whether customer churn can be predicted based on contract, usage, and service-related features, and to identify which model performs better.

*Research Question

Can customer churn be predicted based on customer contract, usage, and service data, and which classification model (Logistic Regression or Decision Tree) provides better predictive performance?

* Dataset

Name: Telco Customer Churn Dataset

Source: Kaggle

Description:
The dataset contains information about customers, including:

Contract type and duration

Monthly and total charges

Internet and additional services

Customer demographics

Target Variable: Churn (Yes / No)

*Methodology
1. Data Preprocessing

Removal of irrelevant features (e.g., customer ID)

Handling missing values

Encoding categorical variables using One-Hot Encoding

Feature scaling (for Logistic Regression)

Train-test split (80% training, 20% testing with stratification)

2. Models Implemented

Logistic Regression

Used as a baseline model

High interpretability through model coefficients

Decision Tree Classifier

Captures non-linear relationships

Limited tree depth to prevent overfitting

3. Evaluation Metrics

Accuracy

Confusion Matrix

Precision, Recall, and F1-Score

Model comparison based on test performance

Results

Both models are capable of predicting customer churn.
However, the Decision Tree achieved a higher classification accuracy compared to Logistic Regression, indicating better performance in capturing complex customer behavior patterns. Logistic Regression remains valuable as a transparent and interpretable baseline model.

*Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

*Conclusion

The project demonstrates that customer churn can be effectively predicted using machine learning models. The comparison shows that Decision Trees outperform Logistic Regression in terms of predictive accuracy, while Logistic Regression offers better interpretability. This highlights the importance of model comparison when solving real-world classification problems.

*Authors

This project was developed as part of a university course on applied artificial intelligence.
