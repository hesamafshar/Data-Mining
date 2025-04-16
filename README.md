
# 📊 Data Mining Projects

This repository contains a collection of data mining projects applying classification, clustering, and probabilistic modeling techniques to real-world datasets using Python and Jupyter Notebooks.

---

## 🗂 Project Structure

### 🔹 BNN – Bayesian Network Learning
- **Notebook**: `BNN.ipynb`  
- **Data**: `insurance.bif`  
- **Overview**:  
  Applies the **Chow-Liu Tree algorithm** to learn a Bayesian Network structure from an insurance dataset using the `bnlearn` library. Demonstrates how probabilistic graphical models can be built for reasoning and inference in uncertain environments.

---

### 🔹 Banking Dataset – Classification of Marketing Targets
- **Data Files**:
  - `Banking Dataset - Marketing Targets.csv`
  - `Train/Test` splits for modeling
- **Notebooks**:
  - `Logestic_Regression.ipynb`
  - `DecisionTree.ipynb`
  - `KNN.ipynb`
  - `SVM.ipynb`
- **Overview**:  
  Predicts whether a customer will respond to a marketing campaign using multiple supervised classification algorithms. The project includes:
  - Data preprocessing and handling missing values
  - Model building and hyperparameter tuning
  - Evaluation with confusion matrices, ROC curves, and classification reports

---

### 🔹 Customer Clustering
- **Notebook**: `Clustering.ipynb`  
- **Dataset**: `Customers.csv`  
- **Overview**:  
  Groups customers based on behavioral patterns using unsupervised learning. Likely applies **K-Means** or similar clustering methods. Key steps include:
  - Data visualization
  - Feature scaling
  - Cluster interpretation

---

## 🧰 Tools & Libraries
- Python 3.x  
- Jupyter Notebook  
- `pandas`, `numpy`, `matplotlib`  
- `scikit-learn` for ML models  
- `bnlearn` for Bayesian Networks

---

## 📦 Datasets Summary
| Dataset                          | Purpose            | Format         |
|----------------------------------|---------------------|----------------|
| `insurance.bif`                 | Probabilistic modeling | Bayesian Network format |
| `Banking Dataset - Marketing Targets.csv` | Classification    | CSV (includes train/test) |
| `Customers.csv`                 | Clustering         | CSV            |
