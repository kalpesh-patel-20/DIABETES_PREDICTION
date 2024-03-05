# Diabetes Prediction ML Project

## Overview
This project aims to predict the likelihood of an individual having diabetes based on various health indicators. It utilizes machine learning techniques, specifically logistic regression, to analyze input fields such as "Pregnancies", "Glucose", "BloodPressure", "SkinThickness", "Insulin", "BMI", "DiabetesPedigreeFunction", and "Age", and makes predictions accordingly.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [License](#license)

## Introduction
Diabetes is a prevalent health condition affecting millions of people worldwide. Early detection and management of diabetes are crucial for preventing complications and improving the quality of life. This project leverages machine learning algorithms to predict the probability of an individual having diabetes based on their health indicators.

## Dataset
The dataset used in this project consists of anonymized health data, including information such as "Pregnancies", "Glucose", "BloodPressure", "SkinThickness", "Insulin", "BMI", "DiabetesPedigreeFunction", "Age", and the target variable indicating the presence or absence of diabetes.

## Features
The features used for diabetes prediction include:
- Pregnancies: Number of pregnancies
- Glucose: Plasma glucose concentration
- BloodPressure: Diastolic blood pressure
- SkinThickness: Skin fold thickness
- Insulin: Serum insulin level
- BMI: Body mass index
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age in years

## Model Building
Logistic regression is used as the primary machine learning algorithm for this project. Logistic regression is a popular choice for binary classification tasks, making it suitable for predicting the presence or absence of diabetes based on the provided features.

## Evaluation
The performance of the logistic regression model is evaluated using metrics such as accuracy, precision, recall and F1-score. Cross-validation techniques are employed to ensure the robustness and generalization of the model.

## License
This project is licensed under the [MIT License](LICENSE).
