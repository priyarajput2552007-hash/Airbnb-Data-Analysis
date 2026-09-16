# Airbnb Data Analysis and Price Prediction using Machine Learning

## Project Overview

This project focuses on analyzing Airbnb listing data and predicting listing prices using Data Analytics and Machine Learning techniques.

The project uses the Airbnb NYC 2019 dataset and performs data cleaning, exploratory data analysis, data visualization, feature engineering, and machine learning.

Two regression models are used:

- Linear Regression
- Random Forest Regression

## Objectives

- Explore the Airbnb dataset.
- Clean and preprocess the data.
- Analyze Airbnb listings using Exploratory Data Analysis.
- Create meaningful data visualizations.
- Analyze prices across room types and locations.
- Study reviews, availability, and minimum nights.
- Build Machine Learning models for price prediction.
- Evaluate model performance using MAE, RMSE, and R² Score.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code
- Git & GitHub

## Dataset

The project uses the Airbnb NYC 2019 dataset.

Dataset contains:

- 48,895 listings
- 16 features

Important features include:

- neighbourhood_group
- neighbourhood
- room_type
- price
- minimum_nights
- number_of_reviews
- reviews_per_month
- availability_365
- latitude
- longitude

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
├── requirements.txt
└── .gitignore

## Data Analysis

The project includes visualizations for:

1. Room Type Distribution
2. Price Distribution
3. Listings by Neighbourhood Group
4. Average Price by Room Type
5. Average Price by Neighbourhood Group
6. Top Neighbourhoods
7. Top Hosts
8. Reviews Distribution
9. Availability Distribution
10. Price vs Minimum Nights
11. Correlation Heatmap
12. Room Type vs Neighbourhood Group

## Machine Learning

The following regression models are implemented:

### Linear Regression

Used as a baseline regression model for predicting Airbnb listing prices.

### Random Forest Regression

Used to capture more complex relationships between the input features and Airbnb prices.

## Model Evaluation

The models are evaluated using:

- MAE - Mean Absolute Error
- RMSE - Root Mean Squared Error
- R² Score

## Key Insights

The analysis shows that Airbnb prices vary according to several factors, including room type, neighbourhood, location, minimum nights, reviews, and availability.

The project demonstrates how Data Analytics and Machine Learning can be combined to extract meaningful insights from real-world data.

## Future Scope

Future improvements may include:

- Advanced Machine Learning models
- Hyperparameter tuning
- Additional feature engineering
- Interactive dashboards
- Deployment as a web application
- Real-time Airbnb data analysis

## Author

**Priya Kumari**

Airbnb Data Analysis and Price Prediction using Machine Learning.