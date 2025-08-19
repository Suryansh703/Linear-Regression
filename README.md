
# 📘 Linear Regression

This repository documents my learnings from the **CampusX Linear Regression playlist**.  
I studied **Simple Linear Regression** and implemented it using two approaches:

1. **Closed-form method (Normal Equation)**
2. **Non-closed form method (Gradient Descent)**

---

## 📌 What is Linear Regression?
Linear Regression is a statistical method to model the relationship between:
- **Dependent variable (y)** → Target
- **Independent variable (x)** → Feature

Equation:
\[
y = \beta_0 + \beta_1 x + \epsilon
\]

---

## 🧮 Methods

### 1️⃣ Closed-form Solution (Normal Equation)
- Direct formula: \(\beta = (X^TX)^{-1}X^Ty\)
- Efficient for **small datasets**


### 2️⃣ Gradient Descent
- Iterative optimization to minimize **MSE**
- Suitable for **large datasets**

---

## 📊 Comparison

| Method | Pros | Cons |
|--------|------|------|
| **Normal Equation** | Exact solution, no hyperparameters | Slow for very large data |
| **Gradient Descent** | Works for large datasets, flexible | Needs learning rate tuning |

---

## 📂 Repository Contents
- `code/` → https://colab.research.google.com/drive/1AI_Tf0yC1yzOpb2KDKZU-tngKsbF53m2?usp=sharing
- `examples/` → Demo on datasets  
 

---

## 🚀 Next Steps
- Multiple Linear Regression  
- Polynomial Regression  
- Regularisation (Ridge, Lasso)  

---

## 🎓 Reference
- **CampusX Linear Regression Playlist** (https://youtu.be/dXHIDLPKdmA?si=FpCnhjxVEhzYyVaj)  
