#  Opal Transport Usage Analysis — Sydney

## Overview
An end-to-end data analysis and machine learning project using real 
Sydney Opal card transport data. The project uncovers public transport 
usage patterns across different travel modes, card types, and time 
periods using regression, classification, and clustering techniques.

##  Technologies Used
- Python 3.x
- Pandas & NumPy — data manipulation
- Matplotlib & Seaborn — visualisation
- Scikit-learn — machine learning models

##  Analysis Performed

### Exploratory Data Analysis
- Distribution of trips across transport modes (bus, train, ferry)
- Usage patterns by card type (Adult, Concession, Student)
- Time series trends across months and years

### Machine Learning Models
- **Linear & Polynomial Regression** — predicting trip counts
- **Logistic Regression** — classifying high vs low usage passengers
- **KNN Regression** — trip count prediction
- **K-Means Clustering** — segmenting users by behaviour

### Feature Selection
- Recursive Feature Elimination (RFE) to identify top 5 predictive features

##  Key Insights
1. Train is the most heavily utilised transport mode
2. Adult Opal cards account for the majority of trips
3. Clear seasonal trends visible in time series analysis
4. K-Means revealed 3 distinct passenger behaviour clusters

##  How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook 48310700-Portfolio4.ipynb
```

## Author
Prashant Khanal 