# 🤖 Machine Learning Algorithms Practice

## 📌 Overview

This repository contains hands-on implementations of Machine Learning algorithms using Python and Scikit-Learn.

The goal of this repository is to learn machine learning concepts from both practical and mathematical perspectives by implementing algorithms using libraries as well as from scratch.

Each notebook focuses on understanding the theory, implementation, evaluation, and visualization of machine learning models.

---

## 📚 Notebooks Included

### 01. Simple Linear Regression – Placement Prediction

**Objective:**
Predict student placement packages using CGPA as the input feature.

#### Topics Covered

* Simple Linear Regression
* Data Preparation
* Train-Test Split
* Model Training
* Prediction
* R² Score Evaluation
* Regression Line Visualization

---

### 02. Simple Linear Regression From Scratch

**Objective:**
Build a Simple Linear Regression algorithm from scratch without using Scikit-Learn's LinearRegression class.

#### Topics Covered

* Mathematics Behind Linear Regression
* Custom Linear Regression Class
* Calculation of Slope (m)
* Calculation of Intercept (b)
* Model Training from Scratch
* Prediction Using Custom Model
* Placement Dataset Analysis
* Regression Line Visualization

#### Learning Highlights

* Understanding how Linear Regression works internally
* Implementing the algorithm step-by-step
* Comparing theory with practical implementation
* Strengthening machine learning fundamentals

---

### 03. Multiple Linear Regression Basics

**Objective:**
Understand and implement Multiple Linear Regression using multiple input features to predict a continuous target variable.

#### Topics Covered

* Multiple Linear Regression
* Synthetic Dataset Generation using `make_regression`
* Data Preparation with Pandas
* 3D Data Visualization using Plotly
* Train-Test Split
* Model Training with Scikit-Learn
* Prediction on Test Data
* Model Evaluation (MAE, MSE, R² Score)
* Understanding Coefficients and Intercept

#### Learning Highlights

* Understanding the difference between Simple and Multiple Linear Regression
* Working with multiple independent variables
* Visualizing data in three dimensions
* Interpreting model coefficients
* Evaluating regression model performance
* Building a complete Multiple Linear Regression workflow

---

### 04. Multiple Linear Regression From Scratch

**Objective:**
Build a Multiple Linear Regression algorithm from scratch without using Scikit-Learn's LinearRegression class.

#### Topics Covered

* Multiple Linear Regression
* Mathematics Behind Multiple Linear Regression
* Custom Multiple Linear Regression Class
* Matrix Representation of Data
* Coefficient Calculation Using Normal Equation
* Model Training from Scratch
* Prediction Using Custom Model
* Synthetic Dataset Generation using `make_regression`
* Model Evaluation (MAE, MSE, R² Score)

#### Learning Highlights

* Understanding how Multiple Linear Regression works internally
* Implementing the algorithm without relying on built-in models
* Working with multiple input features
* Learning matrix-based computation in machine learning
* Evaluating regression model performance
* Strengthening machine learning fundamentals through hands-on implementation

---

### 05. Model Evaluation and Metrics

**Objective:**
Understand how to evaluate machine learning regression models using various performance metrics.

#### Topics Covered

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Adjusted R² Score
* Model Performance Comparison
* Error Interpretation
* Regression Evaluation Techniques


#### Learning Highlights

* Understanding the strengths and limitations of different evaluation metrics
* Comparing model performance using multiple metrics
* Interpreting prediction errors effectively
* Learning when to use each evaluation metric
* Building confidence in model assessment and validation

---

### 06. Linear Regression Assumptions Checking

**Objective:**
Understand and validate the key assumptions of Linear Regression to ensure that the model produces reliable and interpretable results.

#### Topics Covered

* Linear Relationship
* Multicollinearity
* Normal Distribution of Residuals
* Homoscedasticity
* No Autocorrelation of Errors
* Residual Analysis
* Correlation Matrix
* Variance Inflation Factor (VIF)
* Q-Q Plot
* Residual vs Predicted Values Plot
* Durbin-Watson Test

#### Learning Highlights

* Understanding why assumptions are important in Linear Regression
* Identifying violations of model assumptions
* Performing residual diagnostics
* Detecting multicollinearity among features
* Evaluating normality of residuals
* Checking constant variance of errors
* Understanding autocorrelation and its impact on model performance
* Building confidence in model validation and interpretation

### 07. Gradient Descent with Fixed Slope (m)

**Objective:**
Understand the core concept of Gradient Descent by keeping the slope (m) fixed and optimizing only the intercept (b) in a Linear Regression model.

#### Topics Covered

* Introduction to Gradient Descent
* Cost Function Minimization
* Gradient Calculation
* Learning Rate
* Epochs and Iterative Optimization
* Intercept (b) Optimization
* Fixed Slope (m) Regression
* Regression Line Visualization
* Parameter Updates Using Gradient Descent

#### Learning Highlights

* Understanding the intuition behind Gradient Descent
* Learning how machine learning models minimize prediction error
* Visualizing the movement of the regression line during training
* Understanding the role of learning rate in optimization
* Building a strong foundation for Logistic Regression and Neural Networks
* Understanding parameter optimization before implementing full Gradient Descent

### 08. Linear Regression From Scratch Using Gradient Descent

**Objective:**
Implement a complete Linear Regression algorithm from scratch using Gradient Descent by optimizing both the slope (m) and intercept (b) iteratively without relying on Scikit-Learn's LinearRegression class.

#### Topics Covered

* Linear Regression Fundamentals
* Cost Function (Mean Squared Error)
* Gradient Descent Optimization
* Learning Rate and Epochs
* Gradient Calculation for Slope (m)
* Gradient Calculation for Intercept (b)
* Parameter Updates Using Gradient Descent
* Custom Linear Regression Class
* Model Training from Scratch
* Prediction Using Custom Model
* Regression Line Visualization
* Model Evaluation Using R² Score

#### Learning Highlights

* Understanding how Gradient Descent trains a Linear Regression model
* Learning the mathematics behind parameter optimization
* Implementing iterative optimization from scratch
* Understanding the effect of learning rate and epochs on convergence
* Building intuition for machine learning optimization algorithms
* Comparing analytical solutions with iterative learning methods
* Strengthening machine learning fundamentals through hands-on implementation

### 09. Batch Gradient Descent

**Objective:**
Understand and implement Batch Gradient Descent for Linear Regression by updating model parameters using the entire training dataset in each iteration.

#### Topics Covered

* Batch Gradient Descent
* Cost Function Minimization
* Gradient Calculation
* Learning Rate
* Epochs and Iterative Optimization
* Simultaneous Optimization of Slope and Intercept
* Parameter Updates Using Full Dataset
* Regression Line Visualization
* Convergence Analysis

#### Learning Highlights

* Understanding how Batch Gradient Descent works internally
* Learning parameter optimization using the complete dataset
* Understanding the relationship between gradients and error minimization
* Visualizing model convergence during training
* Building a strong foundation for advanced optimization techniques
* Understanding the advantages and limitations of Batch Gradient Descent

### 10. Stochastic Gradient Descent

**Objective:**
Understand and implement Stochastic Gradient Descent (SGD) for Linear Regression by updating model parameters using one training example at a time.

#### Topics Covered

* Stochastic Gradient Descent (SGD)
* Cost Function Minimization
* Learning Rate
* Epochs and Iterative Optimization
* Random Sample Selection
* Gradient Calculation for Individual Samples
* Parameter Updates Using Single Data Points
* Convergence Behavior
* Performance Comparison with Batch Gradient Descent

#### Learning Highlights

* Understanding how SGD differs from Batch Gradient Descent
* Learning faster optimization techniques for large datasets
* Understanding noisy gradient updates and convergence
* Implementing SGD from scratch
* Comparing optimization strategies in Machine Learning
* Building intuition for optimization algorithms used in Deep Learning frameworks

### 11. Mini-Batch Gradient Descent

**Objective:**
Understand and implement Mini-Batch Gradient Descent (MBGD) for Linear Regression by updating model parameters using small batches of training examples instead of the entire dataset or a single sample.

#### Topics Covered

* Mini-Batch Gradient Descent (MBGD)
* Cost Function Minimization
* Learning Rate
* Epochs and Iterative Optimization
* Batch Size Selection
* Random Mini-Batch Creation
* Gradient Calculation for Mini-Batches
* Parameter Updates Using Mini-Batches
* Convergence Analysis
* Performance Comparison with Batch Gradient Descent and Stochastic Gradient Descent
* Model Evaluation Using R² Score

#### Learning Highlights

* Understanding the balance between Batch Gradient Descent and Stochastic Gradient Descent
* Learning efficient optimization techniques for medium and large datasets
* Understanding the impact of batch size on model training
* Implementing Mini-Batch Gradient Descent from scratch
* Comparing optimization strategies in Machine Learning
* Understanding why Mini-Batch Gradient Descent is widely used in Deep Learning
* Building intuition for modern optimization algorithms

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Plotly
* Scikit-Learn
* Google Colab

---

## 🎯 Learning Outcomes

Through these notebooks, you will learn:

* Fundamentals of Machine Learning
* Linear Regression Algorithms
* Model Implementation from Scratch
* Matrix-Based Computation
* Model Evaluation Techniques
* Performance Metrics Interpretation
* Data Visualization
* Practical Machine Learning Workflow
* Model Diagnostics
* Assumption Validation Techniques
* Residual Analysis
* Feature Relationship Analysis
* Statistical Validation of Regression Models
* Gradient Descent Optimization
* Learning Rate Tuning
* Cost Function Minimization
* Parameter Optimization Techniques
* Batch Gradient Descent
* Stochastic Gradient Descent
* Optimization Algorithms
* Convergence Analysis
* Gradient-Based Learning
* Mini-Batch Gradient Descent
* Batch Size Optimization
* Efficient Model Training
* Optimization Strategy Comparison
* Deep Learning Optimization Fundamentals

---

## 🚀 Repository Status

### Completed

* ✅ Simple Linear Regression – Placement Prediction
* ✅ Simple Linear Regression From Scratch
* ✅ Multiple Linear Regression Basics
* ✅ Multiple Linear Regression From Scratch
* ✅ Model Evaluation and Metrics
* ✅ Linear Regression Assumptions Checking
* ✅ Gradient Descent with Fixed Slope (m)
* ✅ Linear Regression From Scratch Using Gradient Descent
* ✅ Batch Gradient Descent
* ✅ Stochastic Gradient Descent
* ✅ Mini-Batch Gradient Descent

---

⭐ This repository documents my journey of learning Machine Learning through hands-on coding, mathematical intuition, and practical implementation.
