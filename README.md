# Experiment 7: Bivariate Analysis – Linear and Logistic Regression Modeling

## Aim

To perform **bivariate analysis** using Linear Regression and Logistic Regression models on diabetes datasets.

## Objective

The objective of this experiment is to study relationships between variables and build regression models for predicting continuous and categorical outcomes.

## Datasets

The experiment uses two diabetes datasets:

* **UCI Diabetes Dataset**
* **Pima Indians Diabetes Dataset**

## Topics Covered

* Bivariate analysis
* Linear Regression
* Logistic Regression
* Independent and dependent variables
* Train-test data splitting
* Model training
* Prediction
* R² score
* Classification accuracy
* Regression visualization

## Bivariate Analysis

Bivariate analysis examines the relationship between **two variables**.

In this experiment, the relationship between **Glucose and BMI** is analyzed using Linear Regression.

### Linear Regression

Linear Regression is used to predict a continuous dependent variable based on an independent variable.

In this experiment:

* **Independent Variable:** Glucose
* **Dependent Variable:** BMI

The relationship between Glucose and BMI is visualized using a scatter plot and regression line.

### Model Evaluation

The performance of the Linear Regression model is evaluated using the **R² (R-squared) score**.

A higher R² value indicates that the model explains a greater proportion of the variation in the dependent variable.

## Logistic Regression

Logistic Regression is used for predicting a **binary categorical outcome**.

In this experiment, Logistic Regression is used to predict the presence or absence of diabetes.

### Features Used

The model uses the following features:

* Glucose
* Blood Pressure
* BMI
* Age

### Target Variable

* **Outcome**

  * `0` – No diabetes
  * `1` – Diabetes

### Model Evaluation

The Logistic Regression model is evaluated using **classification accuracy**.

Accuracy represents the percentage of correctly classified observations.

## Data Splitting

The dataset is divided into:

* **Training Data:** 80%
* **Testing Data:** 20%

The training data is used to build the model, while the testing data is used to evaluate its performance.

## Tools and Technologies

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Learning Outcomes

After completing this experiment, the learner will be able to:

* Understand the concept of bivariate analysis.
* Analyze relationships between two variables.
* Build a Linear Regression model.
* Visualize a regression relationship.
* Calculate and interpret the R² score.
* Build a Logistic Regression classification model.
* Split datasets into training and testing sets.
* Calculate classification accuracy.
* Understand the difference between regression and classification.

## Result

Linear Regression and Logistic Regression models were successfully applied to the diabetes datasets. The relationship between **Glucose and BMI** was analyzed using Linear Regression, while diabetes prediction was performed using Logistic Regression.

## Conclusion

This experiment demonstrates how regression techniques can be applied to real-world healthcare data. **Linear Regression** is useful for predicting continuous values, while **Logistic Regression** is suitable for binary classification problems such as predicting diabetes outcomes.
