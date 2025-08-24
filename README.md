# 📘 Linear Regression  

Linear Regression is a fundamental statistical method used to model the relationship between a **dependent variable (Y)** and one or more **independent variables (X)**. It aims to fit the best line (or hyperplane) that minimizes the error between predicted and actual values.  

---

## 🟢 Simple Linear Regression  

### 📌 Definition  
Simple Linear Regression models the relationship between **one independent variable (X)** and a **dependent variable (Y)** by fitting a straight line of the form:  

\[
Y = \beta_0 + \beta_1 X + \epsilon
\]  

where:  
- \( \beta_0 \) = Intercept  
- \( \beta_1 \) = Slope  
- \( \epsilon \) = Error term  

### 🛠️ My Work  
I implemented **Simple Linear Regression** from scratch using **mathematical intuition** (without built-in ML libraries).  
- Developed a **custom class** for training and prediction.  
- Verified performance using the **R² score**.  
- Link: https://colab.research.google.com/drive/1AI_Tf0yC1yzOpb2KDKZU-tngKsbF53m2?usp=sharing
---

## 🔵 Multiple Linear Regression  

### 📌 Definition  
Multiple Linear Regression models the relationship between **two or more independent variables (X₁, X₂, …, Xn)** and a **dependent variable (Y)**. The general equation is:  

\[
Y = \beta_0 + \beta_1 X_1 + \beta_2 X_2 + \cdots + \beta_n X_n + \epsilon
\]  

where:  
- \( \beta_0 \) = Intercept  
- \( \beta_i \) = Coefficient for feature \( X_i \)  
- \( \epsilon \) = Error term  

### 🛠️ My Work  
I also implemented **Multiple Linear Regression** from scratch using **mathematical intuition**.  
- Built a **custom class** for multi-feature regression.  
- Evaluated results using the **R² score**.  
- Link: https://colab.research.google.com/drive/1ynDhaU9SIWxiTSDsVxyDY6p3HIAuIOb6?usp=sharing
---

## 📊 Key Notes  
- Both implementations focus on **understanding the math** behind regression.  
- R² Score was used to validate the model’s performance.  
- This repo is for **educational and learning purposes**, not production ML.  
