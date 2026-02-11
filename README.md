# ml_assignment11
# 📊 Comprehensive Study of Linear Regression Models

## 👨‍💻 Contributors

**Himanshu Patel**

**Prince Kumar Gupta**

---

## 🎯 Project Objective

The objective of this project is to implement and compare different Linear Regression techniques including:

* Simple Linear Regression
* Multiple Linear Regression
* Polynomial Regression
* Ridge Regression
* Lasso Regression

The goal is to perform end-to-end Machine Learning analysis using a student placement dataset and evaluate model performance using standard metrics.

---

## 📁 Dataset Used

**File Name:** `collegePlace_salary_random_inverse.csv`

### Features:

* Age
* Gender
* Stream
* Internships
* CGPA
* Hostel
* HistoryOfBacklogs

### Target Variable:

* Salary / PlacedOrNot (used for regression analysis)

Synthetic salary values were generated with controlled randomness while maintaining an inverse relationship with CGPA for experimental analysis.

---

## ⚙️ Tools & Technologies

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* GitHub (Version Control)

---

## 🔎 Methodology (Step-by-Step Work Done)

### ✅ Part A — Exploratory Data Analysis (EDA)

1. Loaded dataset using Pandas.
2. Displayed basic dataset information using `head()` and `info()`.
3. Generated summary statistics using `describe()`.
4. Checked missing values.
5. Visualized feature distributions using histograms.
6. Detected outliers using boxplots.
7. Generated correlation heatmap using Seaborn.

---

### ✅ Part B — Simple Linear Regression

1. Selected CGPA as independent variable.
2. Built Linear Regression model.
3. Plotted regression line.
4. Interpreted slope and intercept.

---

### ✅ Part C — Multiple Linear Regression

1. Used multiple features (CGPA, Internships, Stream, etc.).
2. Split data into training and testing sets.
3. Trained Linear Regression model.
4. Evaluated performance using:

   * Mean Squared Error (MSE)
   * Root Mean Squared Error (RMSE)
   * R² Score

---

### ✅ Part D — Polynomial Regression

1. Applied PolynomialFeatures (degree = 2).
2. Built polynomial regression model.
3. Compared performance with linear regression.

---

### ✅ Part E — Regularization Techniques

1. Applied Ridge Regression to reduce overfitting.
2. Applied Lasso Regression for feature selection.
3. Compared coefficients and performance.

---

### ✅ Part F — Model Diagnostics

1. Plotted residuals vs predicted values.
2. Validated regression assumptions:

   * Linearity
   * Homoscedasticity
   * Low multicollinearity

---

## 📈 Evaluation Metrics Used

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 🧠 Observations

* Multiple Linear Regression performed better than Simple Linear Regression.
* Polynomial Regression captured non-linear relationships.
* Ridge and Lasso improved model stability.
* CGPA and Internships were important influencing factors.

---

## 📂 Repository Structure

```
Student-Placement-Linear-Regression/
│── collegePlace_salary_random_inverse.csv
│── Linear_Regression_Assignment.ipynb
│── README.md
```

---

## ✅ Conclusion

This project provided practical understanding of regression models, model comparison, and evaluation techniques. The experiment demonstrated how different linear regression approaches can be applied to real-world datasets and analyzed using visualization and performance metrics.

---
