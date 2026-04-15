# Diabetes Diagnosis Prediction Pipeline

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

An end-to-end Machine Learning pipeline designed to predict the onset of diabetes based on diagnostic measurements. This project covers data cleaning, exploratory analysis, and predictive modeling.

## Project Overview
Diabetes is a chronic condition that affects millions globally. Early detection is key to effective management. This project leverages the **Pima Indians Diabetes Dataset** to build a classifier capable of predicting whether a patient has diabetes with high precision.

## The Pipeline
1.  **Data Preprocessing**: Handling missing values (zeros in Glucose/BMI) and feature scaling.
2.  **EDA**: Visualizing correlations between Insulin, Age, and Outcome.
3.  **Modeling**: Implementation of classification algorithms (Logistic Regression, Random Forest).
4.  **Evaluation**: Metrics focused on reducing False Negatives (Recall).

### Evaluation Metrics
We evaluate the model using the $F_{1}$ Score to balance Precision and Recall:
$$F_{1} = 2 \cdot \frac{\text{precision} \cdot \text{recall}}{\text{precision} + \text{recall}}$$

## Repository Structure
* `diabetes_data.csv`: The primary dataset.
* `diabetes_prediction_model.py`: Main Python script for training and evaluation.
* `requirements.txt`: List of dependencies.

## Getting Started
1. Clone the repo:
   ```bash
   git clone [https://github.com/Silent-Ish/A-Machine-Learning-Pipeline-for-Diabetes-Diagnosis-Prediction.git](https://github.com/Silent-Ish/A-Machine-Learning-Pipeline-for-Diabetes-Diagnosis-Prediction.git)
