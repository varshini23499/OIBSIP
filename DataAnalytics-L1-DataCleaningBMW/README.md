# BMW Cars Dataset — Data Cleaning

## Project Overview
This project cleans a raw BMW cars dataset (`BMW_Cars_Pakistan.csv`) sourced from Pakistan's used car market, preparing it for further analysis.

## Steps Performed
1. **Data Loading & Inspection** — Checked shape, data types, missing values, and duplicates.
2. **Missing Value Handling** — Filled numeric columns with median, categorical columns with mode. Dropped the 'Model Year' column due to a very high proportion (~92%) of missing values.
3. **Duplicate Removal** — Checked and removed duplicate rows.
4. **Text Standardization** — Stripped whitespace and standardized casing across categorical columns (Fuel Type, Transmission, etc.).
5. **Outlier Detection** — Used the IQR method to identify outliers in numeric columns (Price, Mileage, Auction Rating).
6. **Data Type Correction** — Verified and corrected column data types.
7. **Final Export** — Saved the cleaned dataset as `bmw_cleaned.csv`.

## Files
- `BMW_Cars_Pakistan.csv` — original raw dataset
- `bmw_data_cleaning.ipynb` — Jupyter notebook with all cleaning code
- `bmw_cleaned.csv` — final cleaned dataset
- `README.md` — this file

## Tools Used
Python, pandas, numpy, Jupyter Notebook

## Author
Alluru Varshini
