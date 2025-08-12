# Fraud Detection Project

This project is a **Fraud Detection pipeline** implemented in Python, using various machine learning techniques to detect fraudulent transactions.

## 📌 Project Overview
The notebook `FraudDetection.ipynb` contains the end-to-end process of:
- Data preprocessing
- Handling class imbalance with **SMOTE** and other techniques
- Exploratory Data Analysis (EDA)
- Feature scaling and transformation
- Dimensionality reduction (PCA, t-SNE, Truncated SVD)
- Model training & evaluation with multiple algorithms:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - SVM
  - KNN
  - Decision Tree
- Hyperparameter tuning using **GridSearchCV** and **RandomizedSearchCV**
- Performance metrics: ROC-AUC, F1-score, Precision, Recall


## 📂 Project Structure
```
FraudDetection.ipynb        # Main notebook
FraudDetection_fixed.ipynb  # Fixed version with corrections
FraudDetection_executed.ipynb # Partially executed notebook for debugging
README.md                   # Project documentation
```
Optional: data files (CSV) required for training should be placed in the same directory.

## 🚀 How to Run
1. Install the required dependencies.
2. Open `FraudDetection_fixed.ipynb` in Jupyter Notebook or JupyterLab.
3. Ensure your dataset is available in the specified path in the notebook.
4. Run all cells sequentially to reproduce the results.

## 📊 Output & Metrics
The notebook outputs:
- ROC & Precision-Recall curves
- Confusion matrices
- Model performance tables
- Visualization of class balancing techniques



