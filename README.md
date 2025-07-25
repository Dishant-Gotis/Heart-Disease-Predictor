# 💓 Heart Disease Predictor

A machine learning project that predicts the likelihood of a patient having heart disease based on clinical and demographic features. Built using the Random Forest Classifier algorithm in Python.

---

## 📌 Objective

To create an AI model that can accurately predict whether an individual has heart disease using patient medical data. This project uses supervised machine learning for binary classification (Disease / No Disease).

---

## 🧾 Dataset

- **Source**: [Kaggle - Heart Failure Prediction Dataset](https://www.kaggle.com/datasets)
- **Records**: 918 samples
- **Target Column**: `HeartDisease` (1 = has disease, 0 = no disease)

### Features Used:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Max Heart Rate
- Exercise Induced Angina
- ST Depression
- ST Slope

---

## ⚙️ Technologies & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## ✅ Preprocessing

- Checked for missing values
- One-hot encoded categorical columns
- Train-test split (80-20)
- Feature alignment between train and test

---

## 🧠 Model Used

- **Algorithm**: `RandomForestClassifier`
- **Reason**:
  - Works well with both numerical and categorical data
  - Handles feature importance and reduces overfitting
  - Ideal for structured datasets

---

## 📊 Results

| Metric       | Value   |
|--------------|---------|
| Accuracy     | ~86%    |
| Precision    | ~0.88   |
| Recall       | ~0.85   |
| F1 Score     | ~0.86   |

---

## 📁 Project Structure

