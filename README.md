# FMCG Warehouse Supply Optimization

## Problem Statement
An FMCG company selling instant noodles was facing a demand and supply mismatch across their warehouses. Where demand is high supply is low and where demand 
is low supply is high — causing inventory cost losses.

## Objective
Build a machine learning model to predict the optimum 
weight of product to be shipped to each warehouse.

## Dataset
- Rows : 25,000
- Columns : 24
- Target : product_wg_ton

## Steps Followed
1. Exploratory Data Analysis
2. Missing value treatment
3. Feature Engineering
4. Label and Ordinal Encoding
5. Model Building and Comparison
6. Feature Importance Analysis

## Models Used
- Linear Regression
- Ridge Regression
- Random Forest
- Gradient Boosting

## Best Model
Gradient Boosting
- R² Score : 0.9946
- RMSE     : 850 tons
- MAE      : 635 tons

## Key Insight
storage_issue_reported_l3m was the most important feature with 98.4% importance — warehouses with storage problems receive more stock to cover losses.

## Tools and Libraries
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

## Author
Dhanush
BCA Graduate | Advanced AI and ML Course

- LinkedIn: linkedin.com/in/dhanush-m-b402372ba
