# Dirty Café Sales — Data Cleaning Project

## 📌 Project Overview
The Dirty Café Sales dataset contains 10,000 rows of transactional café sales records that were intentionally “messy.”  
The goal of this project was to clean the dataset so it’s ready for reliable analysis, addressing:
- Missing values
- Inconsistent formatting
- Incorrect calculations
- Optimizing storage

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Jupyter Notebook

## 🔍 Key Cleaning Steps
1. Handled missing values (`NaN`) and invalid entries like "UNKNOWN" or "ERROR".  
2. Converted columns to correct data types (`int`, `float`, `datetime`, `category`).  
3. Verified and corrected calculated columns (e.g., `Total Spent = Quantity × Price Per Unit`).  
4. Standardized formats (dates, strings).  
5. Optimized memory usage by converting object columns to categorical where appropriate.  

