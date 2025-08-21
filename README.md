# 📘 Linear Regression

---

## 📌 Introduction
Linear Regression is a fundamental statistical method used to model the relationship between a **dependent variable (y)** and one or more **independent variables (x)**.  
The goal is to fit a line (or hyperplane in higher dimensions) that best predicts the target variable.

General Equation:
\[
y = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + \dots + \beta_n x_n + \epsilon
\]

Where:  
- \( y \) = dependent variable (target)  
- \( x_1, x_2, \dots, x_n \) = independent variables (features)  
- \( \beta_0 \) = intercept  
- \( \beta_1, \beta_2, \dots, \beta_n \) = coefficients  
- \( \epsilon \) = error term  

---

## 🟢 Simple Linear Regression
Simple Linear Regression involves **only one independent variable (x)**.  
It fits a straight line that best represents the relationship between input \( x \) and output \( y \).

Equation:
\[
y = \beta_0 + \beta_1 x + \epsilon
\]

### Methods
1. **Closed-form Solution (Normal Equation)**  
   - Direct formula:  
   \[
   \beta = (X^TX)^{-1}X^Ty
   \]  
   - Efficient for small datasets.  

2. **Gradient Descent (Iterative Method)**  
   - Minimizes the cost function (Mean Squared Error):  
   \[
   J(\beta) = \frac{1}{2m} \sum_{i=1}^{m} (h_\beta(x^{(i)}) - y^{(i)})^2
   \]  
   - Update rule:  
   \[
   \beta_j := \beta_j - \alpha \frac{\partial}{\partial \beta_j} J(\beta)
   \]  
   - Scales better for large datasets.  

---

## 🔵 Multiple Linear Regression
Multiple Linear Regression involves **two or more independent variables**.  
It models the relationship between multiple features and a single target variable.

Equation:
\[
y = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + \dots + \beta_n x_n + \epsilon
\]

### Methods
1. **Closed-form Solution (Normal Equation)**  
   - Uses the same formula as SLR:  
   \[
   \beta = (X^TX)^{-1}X^Ty
   \]  
   - Works directly with multiple variables.  

2. **Gradient Descent**  
   - Extends naturally to multiple variables.  
   - Updates all coefficients simultaneously to minimize error.  

---

## 📊 Comparison

| Aspect | Simple Linear Regression (SLR) | Multiple Linear Regression (MLR) |
|--------|--------------------------------|----------------------------------|
| Variables | One independent variable | Two or more independent variables |
| Equation | \( y = \beta_0 + \beta_1x + \epsilon \) | \( y = \beta_0 + \beta_1x_1 + \beta_2x_2 + \dots + \beta_nx_n + \epsilon \) |
| Visualization | Straight line in 2D | Hyperplane in n-D space |
| Use Cases | Predicting outcome with a single factor (e.g., house price based on size) | Predicting outcome with multiple factors (e.g., house price based on size, location, age) |
