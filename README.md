# Telecom Customer Churn Prediction

## Project Overview

This project focuses on analysing and predicting customer churn in the telecommunications industry using Python and Machine Learning.

Customer churn occurs when customers stop using a company’s services. Understanding the factors associated with churn can help telecommunications companies improve customer retention and make better business decisions.

The project uses customer data to explore patterns and build classification models that predict whether an existing customer is likely to stay or leave.

## Problem Statement

Customer retention is an important challenge in the telecommunications industry. Losing customers can affect revenue and business growth.

This project applies machine learning techniques to identify patterns in customer behaviour and predict customer churn.

## Dataset

The dataset used is the **Telecom Customer Churn** dataset from Maven Analytics, obtained through Kaggle.

It contains information relating to:

• Customer demographics

• Services subscribed to

• Contract information

• Payment methods

• Monthly and total charges

• Customer status and churn information

The analysis focuses on existing customers classified as either Stayed or Churned. Customers marked as Joined were excluded from the prediction task.

## Tools and Technologies

• Python

• Pandas

• NumPy

• Scikit-learn

• Matplotlib

• Kaggle Notebooks

• GitHub

## Project Workflow

1. **Data Loading:** Imported the dataset using Pandas.

2. **Data Exploration:** Examined the dataset structure, columns, data types and missing values.

3. **Data Cleaning:** Handled missing values and prepared the data for modelling.

4. **Feature Selection:** Selected relevant customer attributes for prediction.

5. **Data Preprocessing:** Converted categorical variables into numerical representations using one-hot encoding.

6. **Data Splitting:** Divided the dataset into training and validation sets.

7. **Model Training:** Applied machine learning classification algorithms.

8. **Model Evaluation:** Evaluated model performance using classification metrics.

## Machine Learning Models

The following classification algorithms were explored:

• Logistic Regression

• Decision Tree Classifier

• Random Forest Classifier

## Evaluation Metrics

Model performance was evaluated using:

• Accuracy

• Precision

• Recall

• F1-score

• Confusion Matrix

• ROC-AUC Score

## Model Performance
The three classification models were evaluated using Accuracy and ROC-AUC scores.
|  Model |      Accuracy    |  ROC-AUC |
| :---:         |     :---:      |   :---:    |
| Logistic Regression   | 84.67%      |90.77%    |
|Decision Tree       | 84.52%        |89.97%      |
|Random Forest      |    86.87%  |  92.03%    |



### Best Performing Model
Random Forest achieved the highest performance, with an accuracy of **86.87%** and an ROC-AUC score of **92.03%.**

Based on these evaluation metrics, Random Forest performed best among the three models tested.

## Feature Importance
The Random Forest model was used to identify the features that contributed most to its predictions.

The top 10 important features were:
| Feature | Importance |
| --- | --- |
| Tenure in Months |0.111763 |
| Contract (Month-to-Month) |  0.093715 |
| Total Charges |  0.082708 |
| Total Revenue |   0.080702 |
| Number of Referrals |  0.056621 |
| Monthly Charge |  0.053562 |
| Age | 0.049742 |
|Total Long Distance Charges|  0.047610 |
|Average Monthly Long Distance Charges|  0.037219 |
|Average Monthly GB Download| 0.033423 |

 
### Key Observation

Tenure in Months was the most important feature in the Random Forest model, suggesting that the length of time a customer has stayed with the company is an important factor 
in predicting churn.

The results also highlight the importance of contract type and customer spending patterns.

## Project File
• customer-churn-prediction.ipynb – Jupyter notebook containing the project workflow, data analysis, preprocessing, model training and evaluation.

## Conclusion

This project explored customer churn prediction in the telecommunications industry using machine learning techniques.

Three classification models were developed and evaluated: Logistic Regression, Decision Tree, and Random Forest.

The Random Forest model achieved the best performance, with an accuracy of **86.87%** and a ROC-AUC score of **92.03%.**

The feature importance analysis identified customer tenure, contract type, and spending patterns among the most influential features used by the model.

Overall, this project demonstrates how data analysis and machine learning can help telecommunications companies understand customer behaviour and identify customers who may be likely to leave.







**Author:** Favour Adeyemi


**Area of Interest:** Data Analytics | Machine Learning
