# Medical Insurance Cost Predictor 🏥💸

## Overview
This project is an end-to-end Machine Learning pipeline designed to predict individual medical insurance costs based on demographic and personal health data. The core objective of this project is to demonstrate robust data preprocessing, feature engineering, and the implementation of a Multiple Linear Regression model from scratch.

## Dataset
The dataset contains medical records and personal attributes, including:
* **Age:** Age of the primary beneficiary.
* **Sex:** Gender of the policyholder.
* **BMI:** Body Mass Index, indicating body fat based on height and weight.
* **Children:** Number of dependents covered by the insurance plan.
* **Smoker:** Smoking status (Yes/No).
* **Region:** The beneficiary's residential area.
* **Charges:** Individual medical costs billed by health insurance (Target Variable).

## Tech Stack
* **Language:** Python
* **Data Processing & Math:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Multiple Linear Regression)
* **Data Visualization:** Matplotlib

## Machine Learning Pipeline
1. **Exploratory Data Analysis (EDA):** Visualizing feature correlations to understand the hidden relationships in the data, specifically isolating the impact of lifestyle choices on financial cost.
2. **Data Preprocessing & Cleaning:**
   * Executed the "Null Hunt" to handle missing values and ensure mathematical stability.
   * Converted categorical variables (Sex, Smoker, Region) into numerical formats using encoding techniques so the model could properly digest the text data.
   * Applied feature scaling to normalize the distribution of continuous variables.
3. **Model Training:** Built and trained a Multiple Linear Regression model to map the mathematical weights of multiple independent variables against the target medical charge.
4. **Model Evaluation:** Assessed the algorithm's predictive accuracy using standard regression metrics.

## Key Insights
* **The Smoking Penalty:** Smoking status proved to be the single most significant driving factor for higher medical charges.
* **The Compounding Effect:** The data revealed that the interaction between a high BMI and an active smoking status exponentially increases insurance costs compared to either factor alone.

# Clone the entire foundation repository
git clone https://github.com/Vishnu-Ai-Dev/ML_Foundation_Projects.git

# Navigate directly into the medical insurance project folder
CD ML_Foundation_Projects/01_medical_insurance
