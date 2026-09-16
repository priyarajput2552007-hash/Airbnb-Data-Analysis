# Airbnb Data Analysis and Price Prediction using Machine Learning

## Project Overview

This project presents an end-to-end analysis of the Airbnb NYC 2019
dataset using Python, Data Analytics, Exploratory Data Analysis (EDA),
and Machine Learning techniques.

The project focuses on understanding Airbnb listing patterns,
pricing variations, neighbourhood distribution, room types, reviews,
availability, and other important factors.

Machine Learning models are also developed to predict Airbnb listing
prices.

---

## Dataset

The project uses the Airbnb NYC 2019 dataset.

- Dataset: AB_NYC_2019.csv
- Records: 48,895
- Features: 16

The dataset contains information about:

- Listing details
- Host information
- Location
- Room type
- Price
- Minimum nights
- Number of reviews
- Reviews per month
- Availability

---

## Objectives

The main objectives of this project are:

- To understand the Airbnb dataset.
- To clean and preprocess the data.
- To perform Exploratory Data Analysis.
- To visualize important patterns.
- To analyze Airbnb prices across room types and locations.
- To identify useful business insights.
- To prepare data for Machine Learning.
- To build price prediction models.
- To compare Machine Learning model performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

---

## Project Workflow

The project follows these major steps:

1. Data Collection
2. Data Understanding
3. Data Cleaning
4. Missing Value Handling
5. Duplicate Record Checking
6. Exploratory Data Analysis
7. Data Visualization
8. Business Insights
9. Feature Selection
10. Categorical Encoding
11. Train-Test Split
12. Machine Learning
13. Model Evaluation
14. Model Comparison
15. Feature Importance
16. Final Model Selection

---

## Exploratory Data Analysis

The project includes analysis of:

- Room Type Distribution
- Price Distribution
- Listings by Neighbourhood Group
- Average Price by Room Type
- Average Price by Neighbourhood Group
- Top Neighbourhoods
- Top Hosts
- Reviews Distribution
- Availability Distribution
- Price vs Minimum Nights
- Correlation Heatmap
- Room Type vs Neighbourhood Group

---

## Machine Learning Models

Two regression models were developed:

### 1. Linear Regression

Linear Regression was used as a baseline model for Airbnb price
prediction.

Performance:

- MAE: 68.15
- RMSE: 195.52
- R² Score: 0.1359

### 2. Random Forest Regression

Random Forest Regression was used to capture more complex relationships
between the input features and Airbnb prices.

Performance:

- MAE: 63.20
- RMSE: 200.88
- R² Score: 0.0878

---

## Model Comparison

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 68.15 | 195.52 | 0.1359 |
| Random Forest Regression | 63.20 | 200.88 | 0.0878 |

### Final Model

Linear Regression was selected as the final model because it achieved
a lower RMSE and a higher R² Score.

Random Forest achieved a slightly lower MAE, but its RMSE and R² Score
were weaker.

---

## Key Findings

- Entire home/apt listings represent the largest room type category.
- Airbnb prices vary significantly across different room types.
- Listing prices differ across neighbourhood groups.
- Airbnb listings are concentrated in specific neighbourhoods.
- Some hosts manage multiple properties.
- Review counts vary considerably between listings.
- Availability differs across properties.
- Minimum nights do not show a simple linear relationship with price.
- Multiple factors influence Airbnb listing prices.

---

## Project Limitations

- The dataset represents Airbnb listings from 2019.
- Extreme price values can affect model performance.
- Some important pricing factors are not available in the dataset.
- The current models have relatively low R² Scores.
- Advanced hyperparameter tuning was not extensively performed.

---

## Future Scope

The project can be improved by:

- Applying advanced Machine Learning algorithms.
- Performing hyperparameter tuning.
- Adding more location-based features.
- Including seasonal information.
- Performing advanced feature engineering.
- Developing an interactive Power BI or Streamlit dashboard.
- Deploying the price prediction model as a web application.

---

## Project Structure

```text
Airbnb-Data-Analysis/
│
├── data/
│   └── AB_NYC_2019.csv
│
├── notebook/
│   └── Airbnb_Data_Analysis.ipynb
│
├── images/
│
├── reports/
│
├── README.md
└── requirements.txt