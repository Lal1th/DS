# DS
# Emissions Prediction Model

## Overview

This repository contains a machine learning project focused on predicting emissions coverage using historical data from various jurisdictions. The project utilizes Random Forest and XGBoost regression models to predict emissions coverage for the year 2025 based on data from previous years.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Features

- Predicts the share of jurisdiction emissions covered for the year 2025.
- Implements two regression models: Random Forest and XGBoost.
- Visualizes predictions using scatter plots and residual plots.
- Evaluates model performance using various metrics (MAE, MSE, RMSE, R²).

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn

## Data

The dataset includes historical emissions data for various jurisdictions from 2019 to 2024, with the following key columns:

- `Share of jurisdiction emissions covered`
- `2019`
- `2020`
- `2021`
- `2022`
- `2023`
- `2024`
The results of the models will be printed in the console, including metrics such as:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared (R²)
Visualizations of predictions will also be generated, showing actual vs predicted values and residuals.
Please ensure that the data is properly formatted and preprocessed before running the models.

![image](https://github.com/user-attachments/assets/48d0bb12-b4db-4acd-b8a6-4209c3e3c23b)

![image](https://github.com/user-attachments/assets/70e51afc-8ac6-4dc6-a26e-64b26ab88fc8)

![image](https://github.com/user-attachments/assets/b6b914a3-4b38-4142-a510-2a6ea591d47a)


## Installation

To get started, clone the repository and install the required packages:

```bash
git clone https://github.com/Lal1th/Ds.git
cd emissions-prediction-model
pip install -r requirements.txt
