
# 🚀 Customer Churn Prediction – Model Comparison

This project focuses on **predicting customer churn** using three advanced gradient boosting algorithms: **CatBoost**, **LightGBM**, and **XGBoost**.  
The models were auto-tuned and evaluated based on key performance metrics including Accuracy, Precision, Recall, F1-Score, and AUC.

---

## 📊 Model Performance Summary

| Model     | Accuracy | Precision | Recall  | F1-Score | AUC      |
|------------|-----------|------------|----------|-----------|----------|
| **CatBoost** | **0.8521** | **0.6986** | 0.4828  | 0.5710  | **0.8471** |
| LightGBM   | 0.8436    | 0.6655     | 0.4681  | 0.5496  | 0.8319  |
| XGBoost    | 0.8376    | 0.6520     | 0.4363  | 0.5228  | 0.8316  |

---

## 🏆 Best Model – CatBoost

- **Best Accuracy:** `0.8711`
- **Optimized Parameters:**
  ```python
  {'depth': 6, 'lr': 0.1, 'l2': 3}
