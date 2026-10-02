# House Price Prediction — Linear Regression

## Project Overview
This project builds a Linear Regression model to predict house sale prices using the Ames Housing dataset (House Prices - Advanced Regression Techniques).

## Dataset
Source: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) (Kaggle). Not included in this repo due to size — download from the link above.

## Features Used
GrLivArea, BedroomAbvGr, FullBath, OverallQual, YearBuilt, GarageCars, TotalBsmtSF, Neighborhood (one-hot encoded)

## Steps Performed
1. **Data Loading & Feature Selection** — selected 8 key predictive features from the full 81-column dataset.
2. **Missing Value Handling** — filled numeric columns with median, categorical with mode.
3. **Encoding** — one-hot encoded the Neighborhood column.
4. **Train/Test Split** — 80/20 split.
5. **Model Training** — trained a Linear Regression model.
6. **Evaluation** — MAE, RMSE, R² score.
7. **Visualization** — actual vs predicted price scatter plot, feature coefficient analysis.

## Results
- **R²:** 0.8303
- **MAE:** $22,265.27
- **RMSE:** $36,076.50

## Key Insights
Overall quality, living area, and garage capacity are the strongest positive predictors of price. Neighborhood also has a significant impact on value.

## Files
- `house_price_prediction.ipynb` — full notebook with code and outputs
- `actual_vs_predicted.png` — model performance visualization
- `README.md` — this file

## Tools Used
Python, pandas, numpy, scikit-learn, matplotlib, Jupyter Notebook

## Author
Alluru Varshini
