# Task 3: Linear Regression

## Objective
Implement simple and multiple linear regression using the given Housing dataset.

## Dataset
- **Filename:** Housing.csv
- Contains information about house features and their prices.

## Preprocessing
- Converted 'yes'/'no' categorical columns into 1 and 0.
- One-hot encoded 'furnishingstatus'.
- Checked and confirmed no missing values.

## Steps Followed
1. Imported libraries.
2. Loaded and preprocessed the dataset.
3. Split into training and testing sets (80%-20%).
4. Trained a Linear Regression model.
5. Evaluated model performance using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
6. Visualized Actual vs Predicted prices.
7. Displayed feature coefficients.

## Results
- Evaluation metrics (MAE, MSE, R²) were printed.
- The regression line was plotted against the actual data points to understand the model fit.
- Coefficients of each feature were shown.

## Model Evaluation
- Mean Absolute Error (MAE) ~970,043
- Mean Squared Error (MSE) ~1,754,318,687,331
- R² Score ~0.64
