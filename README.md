# Used Car Pricing Analysis

## Overview
Analyzed 350,000+ used car listings from Craigslist to identify the key factors that drive resale value.

## Key Findings
- Average listing price: $19,155
- Most listed manufacturer: Ford
- Every 10,000 miles reduces value by ~$1,104
- Every 1 year newer adds ~$378 in value
- Prices rose sharply post-2015, peaking around 2022 (COVID-era used car boom)

## Tools Used
- Python, Pandas, Matplotlib, Seaborn, Scikit-learn

## Process
1. Loaded and cleaned 426,880 raw listings down to 353,612 usable records
2. Removed unrealistic prices and odometer readings
3. Analyzed pricing trends by manufacturer, mileage, and model year
4. Built a linear regression model to predict price (R² = 0.365, MAE = $8,313)

## Dataset
Craigslist Used Cars Dataset via Kaggle (Austin Reese)
