# Customer Churn Prediction

## 📌 Project Overview
This project aims to predict customer churn using machine learning techniques. By analyzing customer behavior and transaction history, the model identifies potential churners, helping businesses take proactive retention measures.

## 📊 Dataset
- The dataset contains customer demographics, purchase history, and engagement metrics.
- Features include: `CustomerID`, `Age`, `Subscription Length`, `Monthly Spend`, `Contract Type`, and `Churn Status`.

## 🛠️ Tools & Technologies
- **Programming:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Modeling:** Logistic Regression, Decision Trees, Random Forest
- **Visualization:** Seaborn, Matplotlib
- **Notebook Environment:** Jupyter Notebook

## 🔍 Key Steps
1. **Data Preprocessing:** Handled missing values, encoded categorical variables, and performed feature scaling.
2. **Exploratory Data Analysis (EDA):** Identified trends and correlations using visualizations.
3. **Feature Engineering:** Selected and transformed key predictors.
4. **Model Training & Evaluation:** Tested multiple models and selected the best-performing one based on accuracy, precision, and recall.
5. **Results & Insights:** Provided actionable recommendations to improve customer retention.


## Model Evaluation
**Logistic Regression Model**
Accuracy: 82.04%

**Cross-Validation**
Cross-Validation Scores: [0.8034, 0.8119, 0.7921, 0.8104, 0.8040]
Mean Cross-Validation Score: 80.43%
Feature Importance (Random Forest)
The most important features in predicting customer churn are:

TotalCharges (20.38%)
MonthlyCharges (17.06%)
Tenure (16.33%)
InternetService_Fiber optic (3.49%)

**Key Insights**
The model performs well with an accuracy of 82%, but there is a notable imbalance between churn and non-churn classes.
TotalCharges, MonthlyCharges, and Tenure are the top predictors for customer churn.


