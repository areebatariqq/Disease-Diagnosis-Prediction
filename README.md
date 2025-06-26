# Disease-Diagnosis-Prediction

This project focuses on building a machine learning-based diagnostic system that can predict the presence of a disease based on patient medical data. It aims to assist healthcare professionals by providing accurate predictions and interpretability of the decision-making process.

---

## 📁 Dataset

- **Source**: Public medical dataset from [Kaggle](https://www.kaggle.com/) (e.g., Heart Disease, Diabetes, or any UCI-based dataset depending on your project)
- The dataset contains patient records with features such as age, blood pressure, glucose level, BMI, cholesterol, and other medical indicators, along with a target label indicating disease presence.

---

## 📌 Project Objective

- To build a predictive model that can accurately diagnose diseases based on medical data.
- To interpret model predictions using explainability tools like **SHAP** or **LIME**.
- To offer insights into critical health indicators influencing disease risk.

---

## 🔧 Tools and Technologies Used

- **Google Colab** (for development)
- **Python**
- **Pandas, NumPy, Matplotlib, Seaborn** (EDA and preprocessing)
- **Scikit-learn** (modeling and evaluation)
- **XGBoost, Random Forest, Logistic Regression** (models)
- **SHAP / LIME** (for model interpretability)

---

## 📊 Steps Performed

### 1. Exploratory Data Analysis (EDA)
- Visualized distribution of patient features.
- Checked for missing values, outliers, and correlations.
- Identified key features associated with disease presence.

### 2. Data Preprocessing
- Handled missing or inconsistent data.
- Applied scaling or normalization techniques.
- Encoded categorical variables and performed train-test split.

### 3. Model Training & Evaluation
- Trained multiple models:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier
- Evaluated performance using:
  - **Accuracy**
  - **Precision, Recall, F1-Score**
  - **ROC-AUC Curve**

### 4. Explainable AI
- Used **SHAP** to visualize feature contributions to model predictions.
- Interpreted which features were most influential in diagnosing the disease.

---

## ✅ Results

- **Best Performing Model**: XGBoost (highest ROC-AUC and F1-score)
- **Top Influencing Features**:
  - Glucose level
  - BMI
  - Age
  - Blood pressure
  - Cholesterol

---

## 💡 Insights and Applications

- The model highlights key risk factors that can be monitored for early detection.
- SHAP explanations help clinicians understand **why** a prediction was made.
- This system can be integrated into healthcare applications for decision support.

---
