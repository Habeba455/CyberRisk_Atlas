# 🌐 Cybersecurity Index Prediction & Classification

This project analyzes global cybersecurity indexes and uses machine learning to:

- Predict CEI (Cybersecurity Exposure Index) using regression.
- Classify countries based on CEI risk levels using classification models.

---

## 📊 Dataset

The dataset includes 193 countries with the following features:

- **CEI** (Cybersecurity Exposure Index)
- **GCI** (Global Cybersecurity Index)
- **NCSI** (National Cybersecurity Index)
- **DDL** (Digital Development Level)
- **Region** (Continent of the country)

---

## ⚙️ Models Used

- **XGBoost Regressor**: to predict CEI
- **XGBoost Classifier**: to classify country cybersecurity risk level

---

## 🔍 Evaluation Metrics

- For Regression:
  - Mean Squared Error (MSE)
  - R² Score

- For Classification:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - AUC ROC

---