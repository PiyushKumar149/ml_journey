# 📅 Day 07 – Parameters, Hyperparameters, Gradient Descent & Linear Regression Fundamentals

**📆 Date:** 11 July 2026

---

## 📚 Topics Covered

### 1. Parameters
Parameters are the values learned by a machine learning model during training.

Examples:
- Weight (w)
- Bias (b)

The model automatically updates these values to minimize the loss function.

---

### 2. Hyperparameters

Hyperparameters are values set before training begins. They control the learning process and are not learned from the data.

Examples:
- Learning Rate
- Number of Epochs
- Batch Size
- Number of Hidden Layers
- Regularization Parameter

#### Types of Hyperparameters
- **Model Hyperparameters:** Define the model structure (e.g., number of layers, polynomial degree).
- **Optimization Hyperparameters:** Control the training process (e.g., learning rate, batch size, epochs).

---

### 3. Gradient Descent

Gradient Descent is an optimization algorithm used to minimize the loss function by updating the model's parameters.

#### Working Principle
1. Initialize parameters randomly.
2. Calculate the loss.
3. Compute the gradients.
4. Update the parameters.
5. Repeat until the loss is minimized.

#### Types of Gradient Descent
- Batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-Batch Gradient Descent

---

### 4. Linear Regression Intuition

Linear Regression is a supervised machine learning algorithm used to predict continuous numerical values by finding the best-fit straight line through the data.

Example:
- Predicting house prices
- Predicting salary based on years of experience
- Predicting sales

The goal is to minimize the difference between the predicted and actual values.

---

### 5. Mathematics of Linear Regression

Linear Regression Equation:

**y = wx + b**

Where:
- **y** = Predicted value
- **x** = Input feature
- **w** = Weight (Slope)
- **b** = Bias (Intercept)

The model learns the optimal values of **w** and **b** using Gradient Descent by minimizing the Loss Function.

---

## 📝 Key Learnings

- Learned the difference between parameters and hyperparameters.
- Understood different types of hyperparameters.
- Learned how Gradient Descent minimizes the loss function.
- Explored different types of Gradient Descent algorithms.
- Built intuition for Linear Regression.
- Understood the mathematical equation behind Linear Regression.

---

## 🎯 Progress

- ✅ Day 07 Completed
- 📅 Date: 11 July 2026

---

## 🚀 Next Goal

Implement Linear Regression in Python using Scikit-learn and understand evaluation metrics.
