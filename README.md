# Comparative Analysis of Machine Learning Models for Predicting Pulmonary Tuberculosis Treatment Outcomes

## Project Overview

This project focuses on comparing Machine Learning and Deep Learning models for predicting pulmonary tuberculosis treatment outcomes. The study uses patient data from the Office of Disease Prevention and Control 1, Chiang Mai, to classify treatment outcomes into two groups: successful and unsuccessful outcomes.

## Objectives

- Develop and compare four models: XGBoost, Random Forest, CatBoost, and Artificial Neural Network (ANN).
- Classify pulmonary tuberculosis treatment outcomes based on WHO categories.
- Evaluate model performance, with a focus on Accuracy and Recall.

## Dataset

- **Number of records:** 25,239
- **Data source:** Office of Disease Prevention and Control 1, Chiang Mai, Thailand
- **Target variable:** Treatment Outcome (Successful / Unsuccessful)

*Note: The original patient dataset is not included in this repository due to data privacy concerns.*

## Methodology

1. Data Preprocessing and Feature Preparation
2. Data Splitting (80:20)
3. Model Training and Hyperparameter Optimization
4. Model Evaluation and Comparison

## Model Performance

The performance of the four models was evaluated using Accuracy, Precision, Recall, and F1-Score.

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| XGBoost | 93.99% | 92.13% | 89.59% | 90.78% |
| Random Forest | 93.78% | 91.53% | 89.60% | 90.52% |
| CatBoost | 93.88% | 91.86% | 89.56% | 90.64% |
| ANN | 92.95% | 89.74% | 89.15% | 89.44% |


## Web Application

A web application was developed using Streamlit to allow users to input patient information and view predictions from the trained XGBoost model.

**Application Preview**

[Add Streamlit application screenshot here]

## Disclaimer

This project was developed for educational and research purposes only. The predictions should not be used as a substitute for professional medical diagnosis or treatment decisions.
