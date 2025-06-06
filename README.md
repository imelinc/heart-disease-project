# 🩺 Heart Disease Prediction Project

This project uses the classic UCI Heart Disease dataset to build a machine learning pipeline that predicts the presence of heart disease in patients based on clinical data.

## 🤔 What’s Included

- **📊 Data Exploration & Visualization**
    - Analysis of feature distributions, correlations, and missing values
    - Visualization of class distribution and relationships between key features

- **💾 Data Preprocessing**
    - Handling missing values
    - One-hot encoding of categorical variables
    - Scaling of numerical features

- **🔟 Binary Target Conversion**
    - The multiclass target variable (0-4) is binarized:
        - `0` = no heart disease
        - `1,2,3,4` = presence of heart disease

- **🤖 Model Building**
    - Pipeline including preprocessing and a Random Forest classifier
    - Train-test split with stratification

- **🔥 Hyperparameter Tuning**
    - GridSearchCV for optimal model parameters

- **🧪 Model Evaluation**
    - Accuracy, recall, precision, F1-score
    - Confusion matrix

## 📈 Results

- The tuned model achieves an accuracy of 0.83 on the test set while the baseline model was slightly better with **0.84**.
