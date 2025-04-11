# DSL251 - Data Analysis on Food Delivery

This project involves analyzing food delivery data collected through a survey conducted at IIT Bhilai. The dataset provides insights into food delivery patterns and factors influencing the time it takes for food to reach the hostel.

## Dataset Description

The dataset consists of 4 columns:

1. **Delivery Time**: The time (in minutes) it took for the food to reach the hostel.
2. **Distance**: The distance (in kilometers) between the restaurant and IIT Bhilai.
3. **Time of Day**: The time of day when the order was placed (e.g., morning, afternoon, evening, or night).
4. **App Name**: The name of the food delivery app used to place the order.

## Project Goals

1. **Exploratory Data Analysis (EDA)**: 
   - Analyze the distribution of delivery times and distances.
   - Study the impact of time of day and app choice on delivery time.
   - Identify correlations between features.

2. **Regression Modeling**:  
   - Build and train a regression model to predict the delivery time based on the given features.
   - Evaluate model performance using appropriate metrics (e.g., RMSE, R²).

## Steps Completed

1. **Data Collection**:
   - Conducted a survey to gather data from students at IIT Bhilai.
2. **Data Preprocessing**:
   - Cleaned the dataset by handling missing values and outliers.
   - Encoded categorical variables (e.g., time of day and app name).
3. **EDA**:
   - Visualized feature distributions using histograms and box plots.
   - Explored relationships between variables using scatter plots and correlation matrices.
4. **Modeling**:
   - Used regression models to predict delivery time:
     - Linear Regression
     - Random Forest Regression
   - Tuned hyperparameters for optimal performance.

## Results

- The regression models provide a reliable estimate of delivery time based on the available features.
- The **distance** and **time of day** are significant factors influencing delivery time.

## Future Work

- Extend the dataset by collecting more data to improve model accuracy.
- Explore advanced machine learning models like Gradient Boosting or XGBoost for better predictions.
- Integrate weather conditions and traffic data for a comprehensive analysis.


## How to Use

1. Clone the repository:
   ```bash
   https://github.com/iamshashankyadav/DSL251-data-analysis.git
