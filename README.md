# Customer Churn Prediction Model

## Project Overview

This project aims to predict customer churn using machine learning techniques. Customer churn refers to the phenomenon where customers stop using a company's product or service. By predicting which customers are likely to churn, businesses can take proactive measures to retain them, thereby improving customer satisfaction and revenue.

## Dataset

The dataset used for this project includes various customer attributes and their churn status. The features in the dataset are as follows:

- **RowNumber**: Row number in the dataset (not used for prediction)
- **CustomerId**: Unique ID for each customer
- **Surname**: Surname of the customer
- **CreditScore**: Credit score of the customer
- **Geography**: Country of the customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Tenure**: Number of years the customer has been with the company
- **Balance**: Account balance of the customer
- **NumOfProducts**: Number of products the customer is using
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated salary of the customer
- **Exited**: Whether the customer has churned (1 = Yes, 0 = No)

## Project Notebook

The complete project notebook is available [here](https://github.com/YourUsername/Customer-Churn-Prediction/blob/main/Customer_Churn_Prediction.ipynb). It includes the following steps:

1. **Data Exploration and Preprocessing**:
    - Load and inspect the dataset.
    - Handle missing values.
    - Encode categorical variables (e.g., Geography, Gender).
    - Feature scaling and normalization.

2. **Exploratory Data Analysis (EDA)**:
    - Visualize the distribution of features.
    - Analyze the correlation between features and churn.
    - Identify key factors that influence customer churn.

3. **Model Building**:
    - Split the data into training and testing sets.
    - Train multiple machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost).
    - Evaluate model performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

4. **Model Evaluation and Selection**:
    - Compare the performance of different models.
    - Select the best model based on evaluation metrics.

5. **Prediction and Conclusion**:
    - Make predictions on the test set.
    - Summarize the findings and conclusion.

## Results

The results of the model evaluation and the final predictions on the test set are included in the project notebook. The best performing model achieved high accuracy and provided insights into the most important features influencing customer churn.

## Conclusion

This project demonstrates the application of machine learning techniques to predict customer churn. By leveraging data preprocessing, exploratory data analysis, and model evaluation, we can build accurate predictive models and gain valuable insights into churn prediction.
