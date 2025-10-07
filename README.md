# Credit-Card-Fraud-Detection-using-Logistic-Regression
This project uses Logistic Regression, a supervised machine learning algorithm, to classify transactions as fraudulent (1) or non-fraudulent (0) based on transaction data.
Dataset

Dataset Name: Credit Card Fraud Detection Dataset (Kaggle)
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download


**Description:**

The dataset contains transactions made by European cardholders in September 2013.
It includes 284,807 transactions, out of which 492 are frauds (highly imbalanced data).

**Features**:

V1, V2, …, V28 → Principal components obtained using PCA

Time → Seconds elapsed between each transaction and the first transaction

Amount → Transaction amount

Class → Target variable (0 = Non-Fraud, 1 = Fraud)

**Technologies Used**

Python

Pandas – Data manipulation

NumPy – Numerical computation

Matplotlib / Seaborn – Data visualization

**Project Workflow**

1. Data Preprocessing

Load the dataset using pandas

Handle missing values (if any)

Standardize Amount and Time features

Split dataset into training and testing sets

2. Data Imbalance Handling

The dataset is highly imbalanced (fraudulent transactions are less than 0.2%).
To handle this:

Use Under-sampling or Over-sampling (SMOTE) techniques

3. Model Building

Implement Logistic Regression model from sklearn.linear_model

Train the model using training data

Predict on test data

**Results**

Logistic Regression performs well in identifying fraudulent transactions, especially when recall and precision are prioritized.

The final model can accurately classify most frauds while keeping false positives low.
Scikit-learn – Machine Learning (Logistic Regression, model evaluation)
