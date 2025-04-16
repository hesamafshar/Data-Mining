
# Machine Learning Projects

This repository contains multiple machine learning projects exploring supervised and unsupervised learning techniques using real-world datasets. Each project includes Jupyter Notebooks with code, results, and visualizations.

## 📁 Project Structure

### 🔹 BNN (Bayesian Network using Chow-Liu Tree)
- **Notebook**: `BNN.ipynb`
- **File**: `insurance.bif`
- **Summary**:  
  Implements a Bayesian Network using the Chow-Liu algorithm on the insurance dataset. The notebook uses the `bnlearn` library to construct and visualize the DAG, compute dependencies, and evaluate probabilistic inference.

---

### 🔹 Banking Dataset – Marketing Targets
- **Data Files**:
  - `Banking Dataset - Marketing Targets.csv` (full data)
  - `Train` / `Test` splits available separately
- **Notebooks**:
  - `Logestic_Regression.ipynb`: Logistic Regression with imputation pipelines for missing data, model evaluation with ROC and confusion matrix.
  - `DecisionTree.ipynb`: Decision Tree classifier with grid search and ROC/CM visualizations.
  - `KNN.ipynb`: K-Nearest Neighbors classifier with hyperparameter tuning and performance analysis.
  - `SVM.ipynb`: Support Vector Machine classifier with scaling, grid search, and model evaluation.
- **Summary**:  
  These notebooks aim to classify customer response to marketing using various classification models. Each notebook compares performance and explores feature preprocessing and tuning strategies.

---

### 🔹 Clustering
- **Notebook**: `Clustering.ipynb`
- **Dataset**: `Customers.csv`
- **Summary**:  
  Applies clustering (likely K-Means or similar) to customer data to group clients based on spending behavior. Data preprocessing and visualization of clusters are included.

---

## 🛠️ Technologies Used
- Python 3.x
- Jupyter Notebook
- `scikit-learn`, `matplotlib`, `pandas`, `numpy`
- `bnlearn` (for Bayesian Network)

---

## 📊 Datasets
- **Insurance Dataset** (for BNN)
- **Banking Dataset** (Marketing target classification)
- **Customer Dataset** (Unsupervised clustering)


3. Launch notebooks  
   ```bash
   jupyter notebook
   ```

---
