# Task7_AI_ML_Internship

# 🧠 Support Vector Machines (SVM)  
### Linear & Non-Linear Classification using Scikit-learn

---

## 🎯 Objective

The main objectives of this project are:

- Understand how SVM works
- Implement Linear and RBF Kernel SVM
- Visualize decision boundaries in 2D
- Tune hyperparameters (`C` and `gamma`)
- Evaluate model using cross-validation

---

## 🛠 Technologies

- **Python 3.x**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**

---

## 📂 Dataset Information

- Dataset: Breast Cancer Dataset (built-in from Scikit-learn)
- Type: Binary Classification
- Classes:
  - `0` → Malignant
  - `1` → Benign

For visualization purposes, only the first two features are used.

---

## ⚙️ Project Workflow

### 1️⃣ Import Libraries
Load required libraries: NumPy, Matplotlib, Scikit-learn.

### 2️⃣ Load Dataset
Load dataset using:
```python
from sklearn import datasets
data = datasets.load_breast_cancer()

### 3️⃣ Select Features for 2D Visualization

For visualization of decision boundary, we select only the first two features:

```python
X = data.data[:, :2]
y = data.target
