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

### 1. Data Preparation

* Imported the dataset for binary classification.
* Performed preprocessing such as handling missing values and encoding.
* Split the data into training and testing sets.
* Applied feature scaling to standardize input variables.

### 2. Model Training

* Implemented SVM with:

  * **Linear Kernel**
  * **RBF Kernel**
* Trained both models and compared their classification results.

### 3. Decision Boundary Visualization

* Reduced data to 2D (if required) for visualization.
* Plotted decision regions to understand how SVM separates classes.
* Observed margin maximization and support vectors.

### 4. Hyperparameter Optimization

* Experimented with different values of:

  * **C** (controls regularization strength)
  * **gamma** (controls influence of data points in RBF)
* Selected optimal parameters based on performance.

### 5. Model Evaluation

* Evaluated models using:

  * Accuracy Score
  * Cross-Validation
* Compared performance of linear and RBF kernels.

