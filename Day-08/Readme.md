# 📅 Day 08 – Building Linear Regression from Scratch

**Date:** 12 July 2026

## 📌 Overview
Today, I implemented the **Linear Regression algorithm from scratch** using Python and NumPy without relying on machine learning libraries like Scikit-learn. This helped me understand how Linear Regression learns from data by minimizing the prediction error using Gradient Descent.

---

## 📚 What I Learned

- Understanding the workflow of Linear Regression
- Writing the hypothesis (prediction) function
- Implementing the Mean Squared Error (MSE) cost function
- Computing gradients manually
- Updating weights and bias using Gradient Descent
- Training the model through multiple iterations
- Making predictions on new data

---

## 🧠 Key Concepts

### 1. Hypothesis Function

The Linear Regression model predicts the output using:

\[
\hat{y} = wx + b
\]

Where:
- **x** → Input feature
- **w** → Weight (Slope)
- **b** → Bias (Intercept)
- **ŷ** → Predicted output

---

### 2. Cost Function (Mean Squared Error)

The cost function measures how far the predictions are from the actual values.

\[
J(w,b)=\frac{1}{2m}\sum_{i=1}^{m}(\hat{y_i}-y_i)^2
\]

A lower cost indicates better model performance.

---

### 3. Gradient Descent

Gradient Descent is an optimization algorithm used to minimize the cost function by updating the model parameters.

Weight update:

\[
w = w - \alpha \frac{\partial J}{\partial w}
\]

Bias update:

\[
b = b - \alpha \frac{\partial J}{\partial b}
\]

Where:
- **α** = Learning Rate

---

### 4. Training Process

The training process consists of the following steps:

1. Initialize weight and bias
2. Predict outputs
3. Calculate the cost
4. Compute gradients
5. Update parameters
6. Repeat until convergence

---

## 💻 Skills Practiced

- Python Programming
- NumPy
- Mathematical implementation of ML algorithms
- Gradient Descent
- Cost Function
- Model Training
- Prediction

---

## 🎯 Key Takeaways

- Learned how Linear Regression works internally.
- Understood the role of the Cost Function.
- Learned how Gradient Descent minimizes prediction error.
- Built the algorithm without using Scikit-learn.
- Gained a deeper understanding of model training.

---

## 📂 Files

```
Day-08-Building-Linear-Regression-From-Scratch/
│
├── Linear_Regression_From_Scratch.ipynb
├── README.md
└── dataset.csv (if used)
```

---

## 🚀 Next Goal

- Multiple Linear Regression
- Assumptions of Linear Regression
- Evaluation Metrics (MAE, MSE, RMSE, R² Score)

---

## 📈 Progress

✅ Day 08 Complete

**Machine Learning Journey:** Day 8/∞ 🚀

**#MachineLearning #Python #NumPy #LinearRegression #GradientDescent #AI #DataScience #100DaysOfML**
