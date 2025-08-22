📘 Linear Regression

Linear Regression is a fundamental statistical method used to model the relationship between a dependent variable (Y) and one or more independent variables (X). It aims to fit the best line (or hyperplane) that minimizes the error between predicted and actual values.

🟢 Simple Linear Regression
📌 Definition

Simple Linear Regression models the relationship between one independent variable (X) and a dependent variable (Y) by fitting a straight line of the form:

𝑌
=
𝛽
0
+
𝛽
1
𝑋
+
𝜖
Y=β
0
	​

+β
1
	​

X+ϵ

where:

𝛽
0
β
0
	​

 = Intercept

𝛽
1
β
1
	​

 = Slope

𝜖
ϵ = Error term

🛠️ My Work

I implemented Simple Linear Regression from scratch using mathematical intuition (without built-in ML libraries).

Developed a custom class for training and prediction.

Verified performance using the R² score.

🔵 Multiple Linear Regression
📌 Definition

Multiple Linear Regression models the relationship between two or more independent variables (X₁, X₂, …, Xn) and a dependent variable (Y). The general equation is:

𝑌
=
𝛽
0
+
𝛽
1
𝑋
1
+
𝛽
2
𝑋
2
+
⋯
+
𝛽
𝑛
𝑋
𝑛
+
𝜖
Y=β
0
	​

+β
1
	​

X
1
	​

+β
2
	​

X
2
	​

+⋯+β
n
	​

X
n
	​

+ϵ

where:

𝛽
0
β
0
	​

 = Intercept

𝛽
𝑖
β
i
	​

 = Coefficient for feature 
𝑋
𝑖
X
i
	​


𝜖
ϵ = Error term

🛠️ My Work

I also implemented Multiple Linear Regression from scratch using mathematical intuition.

Built a custom class for multi-feature regression.

Evaluated results using the R² score.

📊 Key Notes

Both implementations focus on understanding the math behind regression.

R² Score was used to validate the model’s performance.

This repo is for educational and learning purposes, not production ML.
