# Bank-churn-customer-prediction
Customer churn prediction using Deep Learning 
# 💳 Bank Churn Customer Prediction

A deep learning-based project to predict customer churn in the banking sector — helping financial institutions proactively retain valuable customers.

---

## 📌 Project Overview

Customer churn — when customers stop using a service — is a critical problem for banks and financial institutions. Using historical customer data, this project leverages a deep learning model to predict the likelihood of a customer leaving the bank.

---

## 🧠 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **NumPy & Pandas**
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for preprocessing and metrics

---

## 🔍 Dataset

The dataset used contains information on bank customers, such as:

- Credit score
- Age
- Tenure
- Balance
- Number of products used
- Whether they have a credit card
- IsActiveMember
- Estimated Salary
- Exited (target label)

You can find similar datasets on [Kaggle](https://www.kaggle.com/datasets) or use the **Churn Modelling dataset**.

---

## 🚀 Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Label encoding categorical features
   - Feature scaling

2. **Model Building**
   - Deep Neural Network using Keras
   - Input layer → Hidden layers with ReLU → Output with sigmoid

3. **Model Training & Evaluation**
   - Train/test split
   - Model training with early stopping
   - Evaluate accuracy, precision, recall, F1-score, and AUC

4. **Results & Visualization**
   - Confusion matrix
   - ROC curve
   - Feature importance analysis (if applicable)

---

## 📈 Sample Results

| Metric       | Score     |
|--------------|-----------|
| Accuracy     | 86%       |
| Precision    | 79%       |
| Recall       | 76%       |
| F1 Score     | 77.5%     |
| AUC          | 0.88      |

---

## 📁 Project Structure

