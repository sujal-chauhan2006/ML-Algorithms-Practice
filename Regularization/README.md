# Ridge Regression From Scratch

## 📌 Overview

This notebook contains my implementation and experimentation with Ridge Regression using both Scikit-Learn and a custom implementation built from scratch using NumPy.

The goal of this notebook is to understand how Ridge Regression works mathematically, how L2 regularization affects model coefficients, and how to implement the algorithm without relying entirely on machine learning libraries.

---

## 🎯 Objectives

* Understand Ridge Regression and L2 Regularization
* Learn how regularization controls model complexity
* Implement Ridge Regression from scratch using NumPy
* Compare custom implementation with Scikit-Learn Ridge
* Analyze the effect of different alpha values
* Visualize Ridge Regression predictions

---

## 📚 Topics Covered

### 1. Ridge Regression Basics

* Linear Regression Review
* Overfitting Problem
* Introduction to Regularization
* L2 Penalty Term
* Alpha (λ) Parameter

### 2. Ridge Regression Using Scikit-Learn

* Training Ridge Models
* Model Prediction
* Coefficient Analysis
* Different Alpha Values

### 3. Ridge Regression From Scratch

* Creating Custom `MeraRidge` Class
* Implementing `fit()` Method
* Implementing `predict()` Method
* Matrix Algebra Operations
* Identity Matrix Construction
* Ridge Normal Equation Implementation

### 4. Multi-Dimensional Ridge Regression

* Working with Multiple Features
* Feature Matrix Transformation
* Coefficient Extraction
* Intercept Calculation

### 5. Model Comparison

* Scikit-Learn Ridge Regression
* Custom Ridge Regression
* Prediction Comparison
* Coefficient Comparison

### 6. Visualization

* Regression Curve Plotting
* Effect of Alpha on Predictions
* Comparing Different Regularization Strengths

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn

---

## ⚙️ Implementation Highlights

### Custom Ridge Regression Class

Implemented a custom Ridge Regression class featuring:

* Configurable alpha parameter
* Manual coefficient calculation
* Manual intercept calculation
* Matrix inversion using NumPy
* Prediction functionality

### Mathematical Implementation

Implemented Ridge Regression using the closed-form solution:

β = (XᵀX + λI)⁻¹Xᵀy

where:

* X = Feature Matrix
* y = Target Variable
* λ = Regularization Strength
* I = Identity Matrix

---

## 📊 Experiments Performed

* Ridge Regression with different alpha values
* Comparison against standard Linear Regression
* Single-feature Ridge Regression
* Multi-feature Ridge Regression
* Diabetes dataset experimentation
* Coefficient shrinkage analysis
* Prediction comparison

---

## 🎓 Key Learnings

* Ridge Regression reduces coefficient magnitude through L2 regularization.
* Increasing alpha increases regularization strength.
* Regularization helps reduce overfitting.
* Matrix algebra plays a major role in implementing machine learning algorithms.
* Ridge Regression can be implemented manually using NumPy operations.
* Custom implementations help build a deeper understanding of machine learning mathematics.

---

## 🚀 Outcome

Successfully implemented Ridge Regression from scratch using NumPy, compared results with Scikit-Learn, explored the impact of regularization strength, and gained hands-on experience with the mathematical foundations of machine learning algorithms.

---

## 📁 File Included

* `Ridge_Regression_from_scratch.ipynb`

---

⭐ This notebook is part of my Machine Learning learning journey, where I implement algorithms both using libraries and from scratch to strengthen conceptual understanding.
