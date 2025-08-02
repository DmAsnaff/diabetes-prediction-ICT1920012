# diabetes-prediction-ICT1920012

# 🧠 Diabetes Prediction using Neural Networks

This project is part of the ICT4302 – Intelligent Systems course. It implements a neural network model to predict whether a patient is likely to be diabetic based on diagnostic medical features. The dataset used is the Pima Indian Diabetes dataset, originally from the National Institute of Diabetes and Digestive and Kidney Diseases.

## 🔍 Project Description

The model was developed using a structured approach:
- Data preprocessing (zero-value handling, imputation, scaling)
- Visualization of feature distributions and class imbalance
- Architecture experimentation (1–4 layers) and overfitting analysis
- Regularization using dropout, L2, batch normalization, and early stopping
- Grid search hyperparameter tuning (units, dropout, L2, learning rate, batch size)
- Final evaluation on a held-out test set using metrics such as ROC-AUC, Precision, Recall, and Confusion Matrix

The best model achieved:
- **Accuracy:** 71.55%
- **ROC-AUC:** 0.789
- **Recall (Class 1):** 47.5%

## 📁 Files

- `diabetes.csv` — Dataset
- `requirements.txt` — List of Python libraries
- `README.md` — This guide
- `feature_distributions.png`, `split_class_distribution.png`, `roc_curve.png`, `conf_matrix.png` — Visualizations
- `grid_search_top_results.csv` — Hyperparameter tuning results (optional)

## ⚙️ Setup Instructions

1. Clone or download the repository.
2. Make sure you have Python 3.7.16 installed.
3. Install required packages:


```bash
pip install -r requirements.txt

## How To run 
open Jupyter notebook and run cells
