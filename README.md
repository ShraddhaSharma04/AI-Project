# Predicting Income Using Online Social Data

This project is an AI/ML-based income prediction system that uses online social and demographic data to predict a person's income level.  
The main goal of this project is to show how machine learning can be used to analyze social behavior, demographic features, and online activity patterns to estimate income.

---

## Project Overview

**Predicting Income Using Online Social Data** aims to use publicly available social indicators to predict income levels in a fast, cost-effective, and privacy-conscious manner.

The project performs data analysis, preprocessing, feature encoding, machine learning model training, and prediction.  
It includes both Python and R-based implementation files for analysis and model building.

---

## Features

- Loads and analyzes social media-based dataset
- Performs data cleaning and preprocessing
- Handles categorical data using label encoding
- Trains a machine learning regression model
- Saves trained model using Joblib
- Saves label encoders for future predictions
- Provides charts and visual reports
- Includes Jupyter Notebook for interactive analysis
- Includes Python and R implementation files

---

## Tech Stack

| Technology | Use |
|---|---|
| Python | Data preprocessing, model training, and prediction |
| R | Statistical analysis and data exploration |
| Jupyter Notebook | Interactive project development |
| Pandas | Data handling and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning model building |
| Joblib | Saving trained model and encoders |

---

## Machine Learning Approach

This project follows a basic machine learning pipeline:

1. Import the dataset
2. Understand the data
3. Clean missing or incorrect values
4. Encode categorical columns
5. Split the dataset into training and testing data
6. Train a regression model
7. Evaluate the model performance
8. Save the trained model
9. Use the saved model for future prediction

---

## Project Structure

```text
AI-Project/
│
├── charts/
│   └── Contains generated charts and visualizations
│
├── for_reports/
│   └── Contains files used for project reports
│
├── Interactive-1.ipynb
│   └── Jupyter Notebook for interactive ML analysis
│
├── Social Meida Dataset.csv
│   └── Dataset used for income prediction
│
├── income_regressor_model.joblib
│   └── Saved trained machine learning model
│
├── label_encoders.joblib
│   └── Saved label encoders for categorical data
│
├── main.R
│   └── R implementation for analysis
│
├── main.py
│   └── Python implementation for model prediction/training
│
└── README.md
    └── Project documentation