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

Please ensure that the data is properly formatted and preprocessed before running the models.

## Installation

To get started, clone the repository and install the required packages:

```bash
git clone https://github.com/Lal1th/Ds.git
cd emissions-prediction-model
pip install -r requirements.txt
