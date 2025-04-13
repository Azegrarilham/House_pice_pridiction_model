# 🏡 Finding the Best ML Model - House Prices Regression

This project tackles the **House Prices - Advanced Regression Techniques** challenge, aiming to predict home sale prices based on 79 features that describe almost every aspect of residential homes in Ames, Iowa.

## 📌 Project Goal

The goal is to **predict the final sale price** for each house in the test set using advanced regression techniques. To achieve this, we experiment with different models and compare their performance based on **Root Mean Squared Error (RMSE)** on the logarithmic scale.

## 📊 Dataset Overview

- **Source:** Ames Housing Dataset, compiled by Dean De Cock
- **Train Set:** `train.csv`
- **Test Set:** `test.csv`
- **Data Description:** `data_description.txt`
- **Sample Submission:** `sample_submission.csv`

The dataset includes features like:

- Property details (e.g., LotArea, YearBuilt, GarageType)
- Building structure and materials
- Neighborhood information
- Interior details (e.g., number of bedrooms, fireplaces, basement quality)

> A full list of features and their descriptions can be found in the data description file.

## 🧠 Practice Skills

- Creative feature engineering
- Handling missing data and outliers
- Model training and evaluation
- Applying techniques like Random Forest, XGBoost, and Gradient Boosting

## 🧪 Evaluation Metric

- **Metric:** Root Mean Squared Error (RMSE) on the log of predicted and actual SalePrice
- Taking logs ensures equal weighting of errors across price ranges.

## 🔧 How to Run

To generate the predictions:

1. Open the notebook file: `theModel.ipynb`

2. Run all cells in order. The notebook includes markdown explanations and step-by-step model training.

3. After execution, the final predictions will be saved as: `House_pice_pridiction_model.csv`

📌 Make sure you have all required libraries installed before running the notebook. You can install them via:

```bash
pip install -r requirements.txt
