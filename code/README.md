# Machine Learning Projects: Regression, Classification, K-Means, and SVM

This repository contains four different machine learning projects that implement key algorithms, including regression, classification, K-Means clustering, and Support Vector Machines (SVM). Each project compares custom implementations to Scikit-learn’s built-in algorithms.

## 📁 Folder Structure

```
├── SVM.ipynb
├── K-means.ipynb
├── regression.ipynb
├── classification.ipynb
├── svm_kernels.ipynb
├── README.md                        # This file
```

## Projects Overview

### 1. **Regression:**
   - **Linear Regression**: Implements Linear Regression from scratch and compares it to Scikit-learn’s Linear Regression and Feedforward Neural Network (FNN) models.
   - **Dataset**: The dataset used contains human cognitive scores for regression analysis.
   - **Goal**: To predict human cognitive scores based on various features.

### 2. **Classification:**
   - **Feedforward Neural Network (FNN)**: Implements a custom Feedforward Neural Network from scratch for binary classification tasks.
   - **Dataset**: Contains a dataset for predicting health risks based on blood test results.
   - **Goal**: To classify the data into risk categories using a custom FNN model.

### 3. **K-Means Clustering:**
   - **From Scratch**: Implements K-Means clustering from scratch using NumPy.
   - **Scikit-learn**: Implements K-Means clustering using Scikit-learn’s optimized version.
   - **Dataset**: Vehicle dataset used for clustering tasks.
   - **Goal**: To cluster the data into `k` clusters and visualize the results.

### 4.1 **Support Vector Machine (SVM):**
   - **From Scratch**: Implements SVM using gradient descent from scratch.
   - **Scikit-learn**: Implements SVM using Scikit-learn's `SVC` class.
   - **Dataset**: Horse dataset used for binary classification.
   - **Goal**: To classify data into two classes using SVM.

### 4.2 **Different SVM Kernels:**
   - **Linear**: Implements SVM using Linear Kernel.
   - **Quadratic**: Implements SVM using Quadratic Kernel.
   - **RBF**: Implements SVM using RBF Kernel.
   - **Goal**: To compare different svm kernels.

## Requirements

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

Install the dependencies:
```bash
pip install pandas numpy matplotlib scikit-learn
```

## Conclusion

This project demonstrates the implementation of key machine learning algorithms, including custom-built models and comparisons to Scikit-learn’s implementations. The projects cover regression, classification, clustering, and support vector machines.
