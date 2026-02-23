# Churn Prediction Analysis

## Overview
This project analyzes customer churn for a museum membership program and builds a predictive model to identify at-risk customers.

## Data Sources
- `data1.csv` - Customer demographic data
- `an13.csv` - Annual visit data (2013)
- `in13.csv` - Individual visit data (2013)

## Outputs
- `predictions.csv` - Churn probability predictions for 78,846 customers
- `churn_analysis_fixed.ipynb` - Complete analysis notebook

## Analysis Components

### Exploratory Data Analysis
- Customer demographics analysis (age, gender distribution)
- Geographic distribution of customers
- Subscription pattern analysis
- Visit behavior patterns
- Time series analysis of visits
- Churn rate analysis by customer segments
- Correlation analysis

### Churn Prediction Model
- **Algorithm**: Random Forest Classifier
- **Features**: age, gender, subscription type, discount, agency type, visit history
- **Performance**: ROC-AUC = 0.779

### Risk Segmentation
- Low, Medium, High risk segments
- Actionable recommendations for each segment

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage
Run the notebook `churn_analysis_fixed.ipynb` to reproduce the analysis.
