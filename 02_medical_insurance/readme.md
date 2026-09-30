# Medical Insurance Cost Prediction (02_medical_insurance)

## 1. Overview
This project is a foundational machine learning implementation that predicts medical insurance costs based on patient demographic and health data. It demonstrates a strict, from-scratch approach to linear regression using gradient descent, bypassing high-level modeling libraries.

## 2. Features
* **Exploratory Data Analysis (EDA):** Verifies dataset integrity (1338 records, 7 features) and evaluates feature relationships using a correlation radar chart to identify primary cost drivers, such as smoking status.
* **Data Preprocessing:** Handles categorical variables via one-hot encoding (dummy variables) and applies Z-score normalization to standardize features for stable training.
* **Mathematical Implementation:** Builds linear regression strictly from scratch using `numpy`, including custom functions for cost computation (`compute_cost`) and gradient calculation (`compute_gradient`).
* **Optimization:** Minimizes the cost function using a custom gradient descent algorithm running for 10,000 iterations with a learning rate of 0.01.

## 3. Directory Structure
```text
02_medical_insurance/
├── insurance.csv             # Raw medical insurance dataset
├── analysis.ipynb            # Exploratory data analysis and correlation mapping
└── linear_regression.ipynb   # Custom gradient descent and model training
```

## 4. Requirements
Execution requires a standard Python data science environment.
* **Python:** 3.10+
* **Core Libraries:** `pandas`, `numpy`
* **Environment:** Jupyter Notebook / IPython

## 5. Execution Steps
Clone the main repository and navigate to the project directory:

```bash
git clone [https://github.com/Vishnu-Ai-Dev/ML_Foundation_Projects.git](https://github.com/Vishnu-Ai-Dev/ML_Foundation_Projects.git)
cd ML_Foundation_Projects/02_medical_insurance
```

1. **Analyze Data:** Open and run `analysis.ipynb` to review dataset dimensions, missing value checks, and feature correlations against the `charges` target variable.
2. **Train Model:** Open and run `linear_regression.ipynb` to execute the normalization sequence, initialize weights/bias to zero, and observe the iterative cost reduction through the custom gradient descent loop.
