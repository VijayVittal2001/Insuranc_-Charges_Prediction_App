# Insurance Charges Predictor using XGBoost & Gradio

This project is a simple machine learning web application that predicts an individual's insurance charges based on their demographic and health-related features. The model uses the `insurance.csv` dataset and is trained using the powerful `XGBoostRegressor`.

The user interface is built with **Gradio**, allowing real-time predictions based on dropdown inputs.

## 🚀 Features

- Machine Learning model trained using XGBoost
- Interactive web UI using Gradio
- Encodes categorical variables using LabelEncoder
- Predicts insurance cost based on:
  - Age
  - Sex
  - BMI
  - Number of children
  - Smoking status
  - Region

## 🧠 Model Details

- Model: `XGBRegressor`
- Evaluation Metrics:
  - R² Score
  - Mean Squared Error
- Dataset: [insurance.csv](https://www.kaggle.com/datasets/mirichoi0218/insurance)

## 🔧 Requirements

Install the necessary Python packages using:

```bash
pip install pandas numpy xgboost scikit-learn gradio
