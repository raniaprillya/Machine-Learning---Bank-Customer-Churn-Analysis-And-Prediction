# Bank Customer Churn Analysis & Prediction

## 1. Source Code
Reference Kaggle notebook: [Bank Customer Churn Analysis and Prediction](https://www.kaggle.com/code/aliaagamal/bank-customer-churn-analysis-and-prediction#4.-Model-Implementation)

---

## 2. Project Overview

### Objective
- Predict whether a bank customer will **churn** (leave) or **stay**, based on customer attributes.  
- Help banks **identify at-risk customers** for retention strategies.  
- Enable **model prediction on new data**.

### Dataset
- Features include demographics, financial information, customer engagement, and customer feedback.  
- Target: `Churn` (1 = left, 0 = stayed).

### Workflow
1. **Data Exploration & EDA** – handle missing values, outliers, and visualize data.  
2. **Data Preprocessing & Cleaning** – encode, normalize, and create derived features.  
3. **Model Building & Tuning** – train and tune ML models.  
4. **Evaluation & Implementation on New Data** – assess model performance and generate predictions for new data.

### Tools & Libraries
- Python 3.x  
- pandas, numpy, scikit-learn  
- matplotlib, seaborn  
- scipy.stats (`chi2_contingency`, `pearsonr`, etc.)  
- feature-engine `Winsorizer`  
- sklearn `StandardScaler`  
- XGBoost, LogisticRegression, RandomForestClassifier  
- GridSearchCV  
- joblib (for model saving)
