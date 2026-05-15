# Opal Dataset Analysis

## Overview
This repository contains an analysis of the Opal dataset, focusing on public transport usage patterns. The goal is to understand passenger behavior through various machine learning techniques, including classification, regression, and clustering. The analysis is performed using Jupyter Notebooks with libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn.

## Dataset
The dataset used for this analysis contains information about public transport trips, including trip counts, card types, and travel modes. It provides insights into how passengers utilize public transport over time.

## Key Steps in the Analysis

### 1. Data Preprocessing
- **One-Hot Encoding**: Categorical variables such as `Card Type` and `Travel Mode` are converted into numerical values for better model interpretation.
- **Binary Target Variable Creation**: A new binary variable `High_Usage` is created to classify users with more than 100 trips.

### 2. Model Development
#### A. Logistic Regression
- Used to classify users based on high usage.
- Performance is evaluated using a classification report and confusion matrix.

#### B. K-Nearest Neighbors (KNN)
- KNN regression predicts the actual number of trips for users.
- Model performance is assessed using Mean Squared Error (MSE).

#### C. K-Means Clustering
- Clusters users based on trip counts and their preferred travel modes.
- Visualization of clusters helps to identify user behavior patterns.

## Evaluation Metrics
- **Classification Report**: Provides precision, recall, and F1-score for the logistic regression model.
- **Confusion Matrix**: Shows the true positives, true negatives, false positives, and false negatives for classification evaluation.
- **Mean Squared Error (MSE)**: Assesses the prediction accuracy of the KNN regression model.

## Insights Gained
1. **High Usage Patterns**: Identifying users with high trip frequency aids in resource planning and service optimization.
2. **Trip Prediction**: KNN provides estimates of expected trips, offering insights into user demand.
3. **Behavioral Clustering**: K-Means clustering reveals distinct user segments, informing targeted marketing and service strategies.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `seaborn`

## Author
Prashant khanal
