# Titanic Survival Prediction - ARTI 308 Lab 2

## 1. Problem Description
The goal of this project is to predict passenger survival on the Titanic based on clinical and demographic parameters (such as age, sex, and passenger class). This is a **Binary Classification** problem, where the target variable is **'Survived'** (1 if the passenger survived, 0 otherwise). The model aims to learn patterns from historical passenger data to determine survival probability.

## 2. Methodology Diagram
This flowchart illustrates the end-to-end machine learning workflow followed in this lab, from problem statement to final deployment.
![Machine Learning Methodology](./Flowchart.png)

## 3. Dataset Information
- **Source:** Titanic Open Dataset (CSV format).
- **Target Variable:** `Survived`.
- **Key Features:** Pclass, Sex, Age, SibSp, Parch, Fare, and Embarked.

## 4. Lab Requirements 
The included Jupyter Notebook (`Titanic_Lab2.ipynb`) performs the following:
- Loads the dataset using Pandas.
- Displays the shape of the data.
- Previews the first few rows.
- Inspects column names and data types.
