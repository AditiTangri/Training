# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 13**

**Date**: 9 July 2025  

## Linear Regression in Machine Learning

Linear regression is a **supervised machine learning algorithm** used to **predict continuous values** by finding the best-fitting straight line through data.

It assumes a **linear relationship** between:
- **Input (X)** – Independent variable  
- **Output (Y)** – Dependent variable

> *As input increases or decreases, output changes at a constant rate.*

---

### Example
Predicting a student's exam score based on hours studied:
- **Input (X)**: Hours studied  
- **Output (Y)**: Exam score

The model learns a pattern from past data and uses that to predict future scores.

---

## Why Linear Regression Is Important
- Simple and Easy to Interpret  
- Useful for Trend Analysis  
- Foundation for Advanced Algorithms (e.g., Logistic Regression)  
- Helps understand relationships between variables  

---

## Best Fit Line

In linear regression, the model finds a **line (y = mx + c)** that best represents the data. This line minimizes the difference between actual and predicted values (residuals).

---

## Assumptions of Linear Regression

1. **Linearity**  
   The relationship between `X` and `Y` is linear.

2. **Independence of Errors**  
   Prediction errors (residuals) should not influence each other.

3. **Constant Variance (Homoscedasticity)**  
   Errors should be evenly spread out across values of X.  
   - Uneven spread = **Heteroscedasticity** (problematic)

4. **Normality of Errors**  
   Residuals should follow a **normal distribution**.

5. **No Multicollinearity** (for multiple regression)  
   Input variables should not be highly correlated with each other.

6. **No Autocorrelation**  
   Errors should not follow a repeating pattern (especially in time series).

7. **Additivity**  
   The total effect on `Y` is the sum of effects from each input variable.

---

## Types of Linear Regression

### 1. Simple Linear Regression
- Uses **one input feature**  
- Equation: `Y = mX + b`  
- Example: Predict salary from years of experience.

### 2. Multiple Linear Regression
- Uses **two or more input features**  
- Equation: `Y = b₀ + b₁X₁ + b₂X₂ + ... + bₙXₙ`  
- Example: Predict house price from size, location, number of rooms.

---

## How It Works

1. **Train the Model**  
   Model learns the best-fit line from training data by minimizing the error (usually using **Least Squares Method**).

2. **Make Predictions**  
   After training, the model can predict `Y` for new, unseen values of `X`.

---


**By**  : Aditi Tangri

**URN**  : 2302460  

**CRN**  : 2315004

