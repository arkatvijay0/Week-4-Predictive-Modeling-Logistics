# Week 4 – Predictive Modeling and Optimization in Logistics Systems

## Project Overview

This project focuses on applying predictive modeling and optimization techniques to a logistics and supply-chain management problem.

The main objective is to develop machine learning models that can classify logistics operations into different risk categories and use the model findings to propose practical optimization strategies.

The project uses a dynamic supply-chain logistics dataset containing shipment, transportation, warehouse, supplier, route, environmental, driver, and operational variables.

The target variable used for prediction is:

- `risk_classification`

The target contains three classes:

- High Risk
- Moderate Risk
- Low Risk

---

## Objectives

The major objectives of this project are:

1. Define a logistics-related predictive modeling problem.
2. Load and inspect the logistics dataset.
3. Perform exploratory data analysis.
4. Clean and preprocess the dataset.
5. Encode categorical variables and scale numerical variables.
6. Develop multiple machine learning classification models.
7. Compare Logistic Regression, Decision Tree, and Random Forest.
8. Perform five-fold cross-validation.
9. Perform hyperparameter tuning using GridSearchCV.
10. Detect and remove target leakage.
11. Evaluate the final leakage-free models.
12. Identify important logistics variables.
13. Propose logistics optimization strategies based on model insights.

---

## Dataset

The dataset contains approximately 32,065 logistics records and 26 variables.

The variables represent different aspects of logistics operations, including:

- Transportation
- Traffic congestion
- Warehouse operations
- Supplier reliability
- Lead time
- Historical demand
- Route risk
- Port congestion
- Shipping costs
- Weather conditions
- IoT temperature
- Cargo condition
- Driver behavior
- Driver fatigue
- Customs clearance

### Target Variable

`risk_classification`

Target classes:

| Class | Description |
|---|---|
| High Risk | Logistics operations with higher potential operational risk |
| Moderate Risk | Logistics operations with moderate potential risk |
| Low Risk | Logistics operations with comparatively lower risk |

---

## Project Workflow

The overall workflow followed in this project is:

```text
Dataset
   ↓
Data Loading and Inspection
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering / Preprocessing
   ↓
Train-Test Split
   ↓
Machine Learning Models
   ↓
Cross-Validation
   ↓
Hyperparameter Tuning
   ↓
Target Leakage Detection
   ↓
Leakage-Free Model Training
   ↓
Final Model Evaluation
   ↓
Feature Importance Analysis
   ↓
Logistics Optimization Recommendations
