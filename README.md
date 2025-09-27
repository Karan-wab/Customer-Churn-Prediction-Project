# Customer-Churn-Prediction-Project

# Customer Churn Prediction for a Bank

## 1. Project Goal
The goal of this project is to analyze the factors that lead to customer churn in a bank and to build a reliable machine learning model to predict which customers are likely to close their accounts. This allows the bank to take proactive steps to retain valuable customers.

---

## 2. Key Features
* **Exploratory Data Analysis (EDA)**: A deep dive into the dataset to identify significant patterns and correlations related to customer churn.
* **Feature Engineering**: Preprocessing of data, including scaling numerical features and one-hot encoding categorical features, to prepare it for modeling.
* **Model Comparison**: Training and evaluation of three different classification algorithms: Logistic Regression, Random Forest, and XGBoost.
* **Performance Evaluation**: Assessment of models based on key metrics like Accuracy, Recall, and ROC-AUC Score to select the most effective one.

---

## 3. Tech Stack & Tools
* **Data Analysis & Modeling**: Python, Pandas, Scikit-learn, XGBoost
* **Data Visualization**: Matplotlib, Seaborn
* **Development Environment**: Jupyter Notebook

---

## 4. File Descriptions
* `Churn_Modelling.csv`: The raw banking dataset containing customer information and the target variable 'Exited'.
* `Customer Churn Prediction.ipynb`: The Jupyter Notebook with the complete Python code for data loading, EDA, preprocessing, model training, and evaluation.

---

## 5. Methodology

### A. Exploratory Data Analysis
The initial analysis revealed several key insights:
* **Geography**: Customers from Germany have a significantly higher churn rate compared to those from France and Spain.
* **Age**: There is a higher probability of churn among middle-aged customers (approx. 40-60).
* **Balance**: Customers with a zero account balance surprisingly show a lower churn rate, while those with very high balances are more likely to churn.

### B. Modeling
Three classification models were trained to predict the `Exited` target variable:
1.  **Logistic Regression**: A baseline model for binary classification.
2.  **Random Forest**: An ensemble model known for its high accuracy.
3.  **XGBoost**: A powerful gradient boosting model, often providing the best performance.

### C. Evaluation
The models were evaluated based on the following metrics:
* **Accuracy**: The overall percentage of correct predictions.
* **Recall**: The model's ability to correctly identify the customers who actually churned. This is a crucial metric for this problem, as failing to identify a churning customer is more costly than mistakenly flagging a loyal one.
* **ROC-AUC Score**: A measure of the model's ability to distinguish between the two classes (churn vs. no churn).

---
