# 🩺 Diabetes Prediction System using Machine Learning

## 📌 Project Overview
This project is a machine learning–based Diabetes Prediction System developed using Python. It predicts whether a patient has diabetes based on medical attributes using a Support Vector Machine (SVM) model. The application also provides model explainability using SHAP and an interactive interface via Streamlit.

---

## 🚀 Features
- Diabetes prediction using SVM (RBF kernel)
- Feature scaling with StandardScaler
- Model evaluation with accuracy and classification report
- SHAP-based model interpretability
- Interactive Streamlit web application
- Model persistence using Joblib

---

## 🗂️ Dataset
- **Dataset Name:** PIMA Indians Diabetes Dataset  
- **Source URL:**  
  https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Streamlit  
- SHAP  
- Matplotlib  
- Joblib  

---

## ⚙️ Project Workflow
1. Load diabetes dataset
2. Split data into training and testing sets
3. Scale features using StandardScaler
4. Train SVM classifier with probability estimates
5. Evaluate model performance
6. Explain predictions using SHAP values
7. Display results using Streamlit

---

## 📊 Model Evaluation
- Model accuracy is displayed in the Streamlit app
- Classification report includes precision, recall, and F1-score

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies
```bash
pip install -r requirements.txt
