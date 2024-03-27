# RandomForestSVMGBT

## Project Title

Stock Market Analysis with Classification Methods and Feature Selection

## Overview

This project applies various classification methods to analyze a stock market dataset and performs feature selection using iterative methods and PCA.

## Key Components

1. **Classification Methods:**
   - Random Forest
   - Gradient Boosting Tree
   - Support Vector Machine (SVM)

2. **Feature Selection:**
   - Iterative Methods
   - Principal Component Analysis (PCA)

## Dataset

The dataset contains the weekly percentage returns for the S&P 500 stock index between 1990 and 2010. The following is the description of the variables:

Year: The year that the observation was recorded
Lag1: Percentage return for previous week
Lag2: Percentage return for 2 weeks previous
Lag3: Percentage return for 3 weeks previous
Lag4: Percentage return for 4 weeks previous
Lag5: Percentage return for 5 weeks previous
Volume: Volume of shares traded (average number of daily shares traded in billions)
Today: Percentage return for this week
Direction: A factor with levels ‘Down’ and ‘Up’ indicating whether the market had a positive or negative return on a given week.
Source: Raw values of the S&P 500 were obtained from Yahoo Finance and then converted to percentages and lagged.

## Results

The analysis reveals insights into the predictive performance of different classification methods and the impact of feature selection techniques on model accuracy and interpretability.
