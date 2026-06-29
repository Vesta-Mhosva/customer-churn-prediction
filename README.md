# Customer Churn Prediction Pipeline

## Project Overview
This project focuses on building an end-to-end machine learning pipeline to predict customer churn. By identifying at-risk customers, businesses can proactively take retention steps.

## Key Findings & EDA
* **Class Imbalance:** The dataset is highly imbalanced, consisting of ~80% retained customers and ~20% churned customers.
* **Demographics:** The majority of the customer base peaks between the ages of 30 and 40.

## Tech Stack & Data Pipeline
* **Data Preprocessing:** Handled categorical encoding using `LabelEncoder` and dropped non-predictive identifiers (IDs, Surnames).
* **Train/Test Split:** Partitioned the data using an 80/20 split.
* **Modeling:** Trained a `RandomForestClassifier` to predict customer exits.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install scikit-learn pandas matplotlib`.
3. Open `Customer_Churn_Prediction.ipynb` in Jupyter Notebook.
