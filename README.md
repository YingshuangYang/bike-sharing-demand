# Bike Sharing Demand Prediction

This project aims to predict the demand for bike-sharing systems using machine learning models.

## Project Overview

- **Objective**: Predict bike-sharing demand.
- **Dataset**: Data contains features like weather, temperature, time, and more.
- **Google Colab Notebook**: You can view and run the notebook directly on Google Colab.

## 🧠 Features

- Data splitting using `train_test_split`
- Scaling with `StandardScaler`
- Model selection: `RandomForestRegressor`, `SVR`, `Ridge`
- Evaluation metrics: MAE, MSE, R²
- Hyperparameter tuning with `GridSearchCV`
- Learning curve visualization
- Custom scoring with `make_scorer`

## Files in this Repository

- **Notebooks**: Contains the Google Colab notebooks for analysis and model training(bike_sharing_demand.ipynb).
- **Dataset**: For training and testing(train.csv and test.csv).
- **Final Report**: A comprehensive summary of the project(Proposal Bike Sharing Demand.pdf).

## Setup

To run this project locally, you can follow the instructions below:
### 1. Clone the repository
```bash
git clone https://github.com/YingshuangYang/bike-sharing-demand.git
cd bike-sharing-demand
```
### 2. Install requirements
```bash
pip install -r requirements.txt
```
### 3. Run the notebook

