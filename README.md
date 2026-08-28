# Titanic Survival Prediction Using Machine Learning
Predict whether a passenger survived the Titanic disaster using machine learning models on classic Titanic dataset. This project involves data cleaning, feature engineering, exploratory data analysis (EDA), and multiple classification algorithms to achieve a high accuracy in survival prediction.

## Table of Contents

- [Overview](#overview)  
- [Features](#features)
- [Project Structure](#project-structure)  
- [Installation](#installation)    
- [Contributing](#contributing)  
- [Dependencies](#Dependencies)  
- [License](#license)
  
## Overview

This repository focuses on predicting the survival of Titanic passengers using machine learning techniques. The approach includes thorough exploratory data analysis, data preprocessing to handle missing data and feature engineering, and evaluating several classification models like Random Forest, Decision Tree, XGBoost, Extra Trees, and Logistic Regression. The final model, Random Forest, achieved an accuracy of approximately **82.68%**.

## Features

- In-depth exploratory data analysis (EDA) to understand data patterns  
- Data cleaning and missing value imputation  
- Feature selection and engineering to improve model performance  
- Model training and evaluation using different classifiers  
- Prediction generation for unseen test data  

## Project Structure
  ```
    Titanic-Survival-Prediction/
    ├── Datasets/
    │ ├── Titanic-Dataset.csv
    ├──Notebook/
    │ ├── Titanc Survivial Prediction.ipynb
    ├── requirements.txt
    ├── Contributing.md
    ├── License
    ├── README.md
    └── titanic-survival-prediction-results.csv
  ```
- `Datasets/` folder contains raw datasets.  
- `Notebook/` contains analysis and modeling code.  
- `requirements.txt` specifies Python dependencies.  
- `README.md` provides project overview and instructions.
- `License` contains the license associated with this project.

## Installation

1. **Clone the repository:**

    ```
    git clone https://github.com/KRUTHIKTR/Titanic-Survival-Prediction.git
    cd Titanic-Survival-Prediction
    ```

2. **Create a Python virtual environment (optional but recommended):**

    ```
    python -m venv venv
    source venv/bin/activate         # On Windows use: venv\Scripts\activate
    ```

3. **Install the required dependencies:**

    ```
    pip install -r requirements.txt
    ```

## Contributing

Contributions are welcome. Please read the [`CONTRIBUTING.md`](https://github.com/KRUTHIKTR/Titanic-Survival-Prediction/blob/main/Contributing.md)) file for guidelines.


## Dependencies

The project requires the Python packages (mentioned in `requirements.txt`)



