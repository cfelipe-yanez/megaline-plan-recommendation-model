# megaline-plan-recommendation-model
Este es el repositorio en el que se creará todo para el proyecto del sprint 10 del curso de Triple Ten 
# Megaline Plan Recommendation Model

## Project Description

In this project, I work with the mobile carrier **Megaline**, which aims to migrate customers from legacy plans to its newer plans: **Smart** and **Ultra**. The company wants to build a machine learning model capable of analyzing customer behavior and recommending the most appropriate new plan for each subscriber.

The dataset contains behavioral data from customers who have already switched to the new plans. Since the data preprocessing stage was completed in a previous project, this task focuses directly on **building and evaluating classification models**.

---

## Project Objective

- Develop a classification model that recommends either the **Smart** or **Ultra** plan
- Achieve the highest possible accuracy
- Meet or exceed the required **accuracy threshold of 0.75**

---

## Dataset Overview

The dataset includes customer behavior metrics such as usage patterns related to calls, messages, and internet consumption. These features are used to predict which plan best fits each user.

The target variable represents the selected Megaline plan:
- `Smart`
- `Ultra`

---

## Methodology

- Load and inspect the dataset
- Split the data into training and validation sets
- Train multiple classification models
- Tune model parameters to improve performance
- Evaluate models using accuracy as the primary metric
- Select the best-performing model based on validation results

---

## Model Evaluation

- Accuracy is used as the main evaluation metric
- The final model is tested against the dataset to confirm it meets the minimum accuracy requirement of **0.75**

---

## Tools and Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## Outcome

The final notebook includes:
- Model training and evaluation
- Comparison of different classification approaches
- Clear justification for the selected model
- Conclusions based on accuracy results

This project demonstrates practical application of machine learning classification techniques in a real business context.
