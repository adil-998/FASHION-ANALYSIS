# Fashion Sales Analysis and Prediction

## Overview
This project analyzes and predicts fashion sales data using exploratory data analysis (EDA), statistical testing, and machine learning models. The goal is to uncover insights about sales trends and build predictive models to forecast sales figures.

## Dataset
- The dataset used is `Snitch_Fashion_Sales_Uncleaned.csv`.
- It contains sales data related to fashion products including features such as product categories, sales units, prices, dates, and regions.

## Key Steps
1. **Data Loading and Cleaning**
   - Loaded the raw dataset using pandas.
   - Handled missing values and cleaned inconsistent entries.
   - Performed data transformations to prepare for analysis.

2. **Exploratory Data Analysis (EDA)**
   - Visualized sales trends over time.
   - Analyzed distribution of sales by product category, region, and other features.
   - Conducted statistical hypothesis tests to identify significant differences.

3. **Model Building**
   - Split data into training and testing sets.
   - Built and trained predictive models including:
     - Random Forest Regressor
   - Evaluated models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²).

4. **Results**
   - Compared model performances.
   - Provided insights into factors affecting fashion sales.

## Requirements
- Python 3.x
- Libraries:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scipy
  - scikit-learn

## How to Run
1. Clone or download the repository.
2. Ensure all dependencies are installed (`pip install -r requirements.txt` or install manually).
3. Run the Jupyter notebook `fashion sale (1).ipynb` step-by-step to reproduce the analysis and results.

## Future Improvements
- Perform hyperparameter tuning for models.
- Incorporate more advanced models like XGBoost or Neural Networks.
- Explore feature engineering for better predictive power.
- Deploy the model into a web app or dashboard for interactive use.

---

*Created by MD Adil Ahmed Shareef*
