# Vehicle Price Analysis and Prediction

This project involves analyzing and predicting vehicle prices using a dataset of car listings from Craigslist. The project demonstrates data cleaning, exploratory data analysis, and predictive modeling using linear regression.

## Features
- **Data Cleaning:** Handled missing values, standardized text fields, and removed unrealistic prices.
- **EDA:** Visualized price distributions, top manufacturers, mileage vs. price, and correlations.
- **Predictive Modeling:** Built a simple regression model to estimate car prices.

## Dataset
- **Source:**([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data/data))
- **File:** `vehicles.csv`

## Tools and Libraries
- Python: Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn for modeling

## Visualizations
1. **Price Distribution:** Understand how car prices vary.
2. **Top Manufacturers:** Identify the top brands by listings.
3. **Mileage vs. Price:** Explore the relationship between mileage and price.
4. **Correlation Heatmap:** Examine correlations between numerical features.

## Predictive Modeling
- Features: `year`, `odometer`
- Target: `price`
- Model: Linear Regression
- Evaluation: Mean Absolute Error (MAE)

## Instructions to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Maisha21/Vehicle_Price_Analysis.git
