# TA2 AI/ML Project – Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.  
The dataset is highly imbalanced and contains anonymized transaction features.

## 📌 Project Overview
- Analyse credit card transactions  
- Handle imbalanced data  
- Train ML models (Logistic Regression & ANN)  
- Evaluate fraud detection performance  
- Visualize patterns and insights  
- Save trained models for deployment  
- Compare performance of ML vs ANN  

## 📂 Files Included

| File Name | Description |
|-----------|-------------|
| `Credit_Card_Fraud_Detection.ipynb` | Main Jupyter Notebook (data preprocessing, EDA, model training, ANN, evaluation) |
| `logistic_model.pkl` | Saved Logistic Regression model using Pickle |
| `scaler.pkl` | Saved StandardScaler for preprocessing |
| `ann_model.h5` | Saved Artificial Neural Network model (Keras HDF5 format) |
| *(Dataset not uploaded)* | Dataset is too large to upload |

## 📊 Dataset Information

The dataset used in this project is publicly available on **Kaggle**:

👉 **Download Dataset:**  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Summary:
- **284,807** transactions  
- **492 fraud cases**  
- **29 input features** (`V1–V28`, `Amount`)  
- **Highly imbalanced** dataset (fraud cases ≈ 0.17%)

## 🧠 Model Saving Information

### ✔ Logistic Regression Model  
Format: **Pickle**  
File: `logistic_model.pkl`

### ✔ StandardScaler  
Format: **Pickle**  
File: `scaler.pkl`

### ✔ Artificial Neural Network (ANN) Model  
Format: **HDF5 (.h5)**  
File: `ann_model.h5`

## 🔍 Model Comparison (ANN vs Logistic Regression)

### **📥 Input Data Used for Comparison**
100, -1.35, 0.55, 2.1, 0.34, -0.28, 0.45, 0.12, -0.18, 0.67,
0.22, -0.31, -0.45, 0.51, -0.80, 0.14, 0.28, -0.19, 0.07,
0.40, 0.12, -0.13, -0.05, -0.02, -0.06, 0.18, -0.38, 0.21,
-0.12, 55

### **📌 Result**
- **Logistic Regression** → Lower performance  
- **ANN (Neural Network)** → Correctly identified the class, performed significantly better  

## 🛠 Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib / Seaborn  
- Jupyter Notebook  

## ▶ How to Run This Project

### 1. Download the dataset
Place `creditcard.csv` in the project folder.

### 2. Open the Jupyter Notebook
```
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

### 3. (Optional) Use saved models for prediction
Load:
- `logistic_model.pkl`  
- `scaler.pkl`  
- `ann_model.h5`
