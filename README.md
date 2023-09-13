# UBER & LYFT Price Prediction


## Project Background and Problem Statement

The dataset for this project was obtained from Kaggle, and it can be accessed [here](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma?resource=download). We aim to analyze the dataset, which contains information about Uber and Lyft rides in Boston, MA, and identify patterns and relationships between various columns. Specifically, we want to understand how factors such as date, time, weather, and demand influence ride prices.

## Goals of the Project

Ride prices on Uber and Lyft are dynamic and can vary significantly based on factors like demand and time of day. Our project's objectives are as follows:

1. Determine the factors that influence the demand for rides.
2. Analyze how ride costs change depending on the time of day and weather conditions.
3. Identify peak surges in demand, particularly during typical commuting hours (9 am to 5 pm).
4. Assess the impact of weather (e.g., rain or snow) on ride frequency.

## Project Details

To achieve our project goals, we followed these steps:

1. **Exploratory Data Analysis (EDA):** We began by gaining a deep understanding of the dataset's features and their relationships with the target variable (ride costs). We used various data visualization techniques to visualize these relationships.

2. **Regression Models:** We implemented four regression models to predict ride costs accurately. These models are:

   - Linear Regressor
   - Decision Tree Regressor
   - Random Forest Regressor
   - Gradient Boosting Regressor

3. **Model Evaluation:** We evaluated the performance of each regression model and calculated their respective scores.

According to the parameters that we used for gauging the model performance, we found that the **Gradient Boosting Regressor** is the best model for Uber/Lyft price predictions.

## Project Results

Here are the scores achieved by each regression model:

- Linear Regressor: 0.4197
- Decision Tree Regressor: 0.9351
- Random Forest Regressor: 0.9465
- Gradient Boosting Regressor: 0.9570

The Gradient Boosting Regressor outperformed the other models with the highest score, making it the best model for predicting ride costs.

## Problem Statement

Throughout this project, we aimed to address the following problem statements:

1. Which days of the week experience the highest fare rates?
2. How do Uber and Lyft dynamically change their pricing for rides?
3. What is the impact of day-to-day rising prices on commuters?
4. Can we analyze the trips, including their duration and cost?
5. How does weather and peak time factors influence ride costs?

This project sheds light on the dynamic nature of ride pricing in Uber and Lyft, providing valuable insights for both commuters and the ridesharing companies themselves.

---
