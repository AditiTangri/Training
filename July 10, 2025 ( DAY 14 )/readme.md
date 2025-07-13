# ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING  
**DAY - 14**

**Date:** 14 July 2025  

## Logistic Regression in Machine Learning

Logistic Regression is a supervised machine learning algorithm used for classification problems.  
Unlike linear regression which predicts continuous values, logistic regression predicts the **probability** that an input belongs to a specific class.  
It is commonly used for **binary classification** where the output can be one of two possible categories such as Yes/No, True/False, or 0/1.  
Logistic regression uses the **sigmoid function** to convert inputs into a probability value between 0 and 1.

---

## Types of Logistic Regression

### 1. Binomial Logistic Regression
- Used when the output has **two categories** (e.g., Yes/No, 0/1)  
- Example: Predicting if a student will pass or fail

### 2. Multinomial Logistic Regression
- Used when the output has **three or more categories** with **no order**  
- Example: Classifying an animal as a cat, dog, or sheep

### 3. Ordinal Logistic Regression
- Used when the output has **ordered categories**  
- Example: Rating a product as low, medium, or high

---

## Assumptions of Logistic Regression

- **Independent Observations**: Each data point must be independent of others  
- **Binary Output**: The dependent variable should be binary (0 or 1), unless using multinomial/ordinal versions  
- **Linearity in Log-Odds**: Predictors should have a linear relationship with the log odds of the outcome  
- **No Extreme Outliers**: Outliers can affect model accuracy  
- **Large Sample Size**: A bigger dataset ensures more reliable results  

---

## How Does Logistic Regression Work?

Logistic Regression is commonly used for classification when the output is binary.

### Step-by-Step Working:

1. **Takes Input Features (X):**  
   Examples: age, income, exam score

2. **Applies a Linear Equation:**  
   Combines inputs with weights to calculate a linear score (z)

3. **Applies the Sigmoid Function:**  
   Converts z to a probability (between 0 and 1) 

4. **Makes Prediction:**  
   - If probability > 0.5 → Predicts class 1 (e.g., "yes")  
   - If probability ≤ 0.5 → Predicts class 0 (e.g., "no")

### Example:
Predicting if a person will buy a product:  
- Inputs: Age = 30, Salary = 50,000  
- Model calculates a score and applies the sigmoid  
- If probability = 0.85 → Predicts "Will Buy"


---


**By**  : Aditi Tangri

**URN**  : 2302460  

**CRN**  : 2315004
