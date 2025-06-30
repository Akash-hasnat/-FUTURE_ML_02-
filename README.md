

# 📊 Customer Churn Prediction

This project predicts customer churn using machine learning models. It includes data cleaning, feature encoding, model training, evaluation, and visual analysis.

---

## 🗂 Dataset

* **Source**: `/content/drive/MyDrive/paper/archive (2).zip`
* **Target**: `Churn`

---

## ⚙️ Workflow

1. **Data Preprocessing**:

   * Handle missing values
   * Encode categorical variables
   * Drop irrelevant columns (`customerID`)
   * Scale features

2. **Models Used**:

   * Logistic Regression
   * Random Forest
   * XGBoost

3. **Evaluation Metrics**:

   * Accuracy, Precision, Recall, ROC-AUC, Classification Report

4. **Feature Importance**:

   * Visualized using Random Forest

5. **EDA Visuals**:

   * Churn distribution
   * Contract type vs churn
   * Monthly charges, tenure, and customer service calls vs churn

---

## 📦 Requirements

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
```

---

## ✅ Run the Code

Use Jupyter Notebook or any Python IDE to execute the script.

---

## 🔍 Insight

Month-to-month contracts, low tenure, and high service calls are key churn indicators.

---


