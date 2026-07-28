# 📊 Food Price & Inflation Prediction System

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uG4xSp0I57lBzQptlhy0qVp_yg5gHWXn?usp=sharing)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **An end-to-end Machine Learning project** developed in Google Colab to predict food prices and analyze inflation trends using historical data.

## 🎯 Project Overview

This project uses **Python** and **scikit-learn** to build a predictive model that forecasts future food prices based on historical trends, seasonal patterns, and economic indicators. The entire analysis, from data cleaning to model evaluation, is performed in an interactive Colab notebook.

## ✨ Key Features

- 📈 **Data Preprocessing:** Handles missing values, outliers, and date formatting.
- 🔍 **Exploratory Data Analysis (EDA):** Visualizes price trends, seasonality, and correlations.
- 🤖 **Multiple ML Models:** Implements and compares Linear Regression, Random Forest, and XGBoost.
- 📊 **Performance Metrics:** Evaluates models using MAE, RMSE, and R² Score.
- 📉 **Future Predictions:** Forecasts prices for the next 3-6 months.
- 📁 **Automated Reporting:** Saves results and visualizations directly to Google Drive.

## 🛠️ Tech Stack (All within Colab)

| Category | Libraries/Tools |
| :--- | :--- |
| **Data Manipulation** | `pandas`, `numpy` |
| **Visualization** | `matplotlib`, `seaborn`, `plotly` |
| **Machine Learning** | `scikit-learn`, `xgboost` |
| **Deep Learning** | `tensorflow` / `keras` (optional for LSTM) |
| **Environment** | Google Colab (with GPU acceleration) |
| **Storage** | Google Drive (for data/models) |

## 🚀 How to Run the Project

This project is designed to run with zero setup in your browser.

### Step 1: Open in Colab
Click the badge at the top of this README or use this link:
[**Open Food Price Predictor in Colab**](https://colab.research.google.com/drive/1uG4xSp0I57lBzQptlhy0qVp_yg5gHWXn?usp=sharing)

### Step 2: Connect to Runtime
- In the Colab menu, click `Runtime` → `Run all`.

### Step 3: (Optional) Connect to Google Drive
- If the notebook saves outputs, run the cell that mounts your Drive:
```python
from google.colab import drive
drive.mount('/content/drive')
