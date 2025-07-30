# Personal Loan Acceptance Prediction

# Objective
Predict whether a customer will accept a **personal loan offer** using the Bank Marketing Dataset. This helps banks improve targeting and reduce marketing costs.

---

# Dataset
- **Source:** UCI Machine Learning Repository(Bank Marketing Dataset availale on Kaggle)
- **Target Variable:** `deposit_yes` — whether the client subscribed to a term deposit

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was conducted using **Power BI** for intuitive and interactive visualizations. Check out the file..


# Approach & Methodology

# 1. **Data Preparation**
- One-hot encoding for categorical variables
- Dropped irrelevant columns
- Split dataset into training and testing sets (`X_train`, `X_test`, `y_train`, `y_test`)

# 2. **Model Training**
- Trained a **Random Forest Classifier**
- Calculated feature importances

# 3. **Feature Selection**
- Dropped features with very low importance 
- Retrained the model using only meaningful features

# 4. **Evaluation**
Accuracy: **82.84**

Confusion Matrix:
 [[948 215]
 [168 902]]

Classification Report:
               precision    recall  f1-score   support

       False       0.85      0.82      0.83      1163
        True       0.81      0.84      0.82      1070

    accuracy                           0.83      2233
   macro avg       0.83      0.83      0.83      2233
weighted avg       0.83      0.83      0.83      2233



