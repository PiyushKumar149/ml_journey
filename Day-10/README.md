# Day 10: Logistic Regression & Implementing Logistic Regression from Scratch

**Date:** 3 August 2026

## 📚 Topics Covered

* Introduction to Logistic Regression
* Why Linear Regression cannot be used for Classification
* Sigmoid (Logistic) Function
* Probability Interpretation
* Binary Classification
* Decision Boundary
* Cost Function (Log Loss / Binary Cross Entropy)
* Gradient Descent Optimization
* Training Logistic Regression from Scratch using NumPy
* Making Predictions on New Data

---

## 📝 What I Learned

Today I learned **Logistic Regression**, one of the most fundamental supervised machine learning algorithms used for **binary classification problems**.

Unlike Linear Regression, Logistic Regression predicts the **probability** that an input belongs to a particular class. The predicted probability is then converted into a class label (0 or 1) using a threshold (commonly 0.5).

I also learned why Linear Regression is not suitable for classification tasks, since it can produce values outside the range of 0 and 1.

The core of Logistic Regression is the **Sigmoid Function**, which transforms any real-valued number into a probability between 0 and 1.

I studied the **Binary Cross Entropy (Log Loss)** cost function and understood how **Gradient Descent** updates the weights and bias to minimize prediction error.

Finally, I implemented the entire Logistic Regression algorithm **from scratch using NumPy**, without relying on Scikit-learn. The implementation included:

* Initializing weights and bias
* Computing the linear model
* Applying the sigmoid function
* Calculating gradients
* Updating parameters using gradient descent
* Training the model over multiple iterations
* Predicting class labels for unseen data

---

## 💻 Technologies Used

* Python
* NumPy
* Google Colab

---

## 🎯 Key Takeaways

* Logistic Regression is used for **binary classification**.
* The Sigmoid Function converts linear outputs into probabilities.
* Predictions are based on a probability threshold.
* Binary Cross Entropy is the loss function used for optimization.
* Gradient Descent updates model parameters iteratively.
* Understanding the mathematics behind Logistic Regression makes implementing it from scratch much easier.

---

## 🚀 Outcome

By the end of Day 10, I understood both the **theoretical concepts** and the **mathematical foundations** of Logistic Regression, and successfully built the algorithm from scratch using Python and NumPy.

#MachineLearning #Python #NumPy #LogisticRegression #Classification #GradientDescent #AI #DataScience #100DaysOfML
