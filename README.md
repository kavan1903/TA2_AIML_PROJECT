# TA2 AI/ML Project – Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.  
The dataset is highly imbalanced and contains anonymized transaction features.

---

## Project Overview
- Analyse credit card transactions
- Handle imbalanced data
- Train ML models (Logistic Regression, Random Forest, etc.)
- Evaluate fraud detection performance
- Visualize data and results

---

## Files Included
| File Name | Description |
|-----------|-------------|
| `Credit_Card_Fraud_Detection.ipynb` | Main Jupyter Notebook containing data preprocessing, analysis, model training & evaluation |
| *(Dataset not uploaded)* | The dataset is large, so it is not included in the repository |

---

## Dataset Information
The dataset used in this project is publicly available on **Kaggle**:

**Download Dataset Here:**  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

This dataset contains:
- 284,807 transactions  
- 492 fraud cases  
- Features are numerical and anonymized (V1–V28)  
- Highly imbalanced dataset

## Model Comparison (ANN vs Logistic Regression)

To compare the prediction performance of **Artificial Neural Network (ANN)** and **Logistic Regression**, the following **sample input feature vector** was used:

### ** Comparison Input Data**
100, -1.35, 0.55, 2.1, 0.34, -0.28, 0.45, 0.12, -0.18, 0.67,
0.22, -0.31, -0.45, 0.51, -0.80, 0.14, 0.28, -0.19, 0.07,
0.40, 0.12, -0.13, -0.05, -0.02, -0.06, 0.18, -0.38, 0.21,
-0.12, 55

### ** Result**
- **Logistic Regression** → lower accuracy on this input  
- **Artificial Neural Network (ANN)** → **performed significantly better**, correctly identifying the class  

✔ ANN handles non-linear patterns, making it more suitable for this dataset.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## How to Run This Project
1. Download the dataset from Kaggle  
2. Place `creditcard.csv` in the same folder as the notebook  
3. Open the notebook:
   ```sh
   jupyter notebook Credit_Card_Fraud_Detection.ipynb
