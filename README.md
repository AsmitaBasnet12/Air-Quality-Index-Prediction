Air Quality Index Prediction

This project focuses on building a machine learning model to predict the Air Quality Index (AQI) based on various environmental features such as pollutant levels, temperature, humidity, and wind speed. The project includes data cleaning, feature engineering, outlier detection, and the application of regression models.

Dataset

The dataset used in this project is sourced from publicly available environmental data.

Key Features:

PM2.5: Particulate Matter 2.5 concentration.

PM10: Particulate Matter 10 concentration.

NO2: Nitrogen Dioxide levels.

SO2: Sulfur Dioxide levels.

CO: Carbon Monoxide levels.

O3: Ozone concentration.

AQI: Air Quality Index (target variable).

Project Workflow

1. Data Cleaning

2. Feature Engineering

3. Outlier Detection and Removal

a. Pollutant Level Outliers:

4. Modeling

Models Used:

Linear Regression

Random Forest Regressor


5. Evaluation

Random Forest Regressor outperformed Linear Regression due to its ability to handle non-linear relationships and interactions between features.

Emphasized the importance of feature engineering and addressing outliers in improving model performance.

How to Use

Prerequisites:

Python 3.7+

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Results

The best-performing model was the Random Forest Regressor with an R² score of 0.85.

The project demonstrated the critical role of preprocessing and the selection of appropriate features and models in achieving accurate predictions.

Future Work

Incorporate more advanced models like Gradient Boosting or XGBoost.

Explore hyperparameter tuning for Random Forest.

Enrich the dataset with additional features like traffic data or industrial activity.

Dataset Acknowledgment

The dataset is sourced from publicly available environmental data.



