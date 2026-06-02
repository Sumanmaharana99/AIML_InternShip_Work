# Linear Regression on Titanic Dataset

## Objective
- Build and evaluate a Linear Regression model on the Titanic dataset.

## Tasks Performed
- Imported the Titanic dataset.
- Handled missing values using median imputation.
- Selected relevant features for prediction.
- Split the dataset into training and testing sets.
- Trained a Linear Regression model using Scikit-Learn.
- Predicted values on the test dataset.
- Evaluated the model using MAE, MSE, and R² Score.
- Visualized the regression line between Age and Fare.

## Results
- MAE: 19.78
- MSE: 946.34
- R² Score: 0.388

## Key Findings
- Age has a weak positive relationship with Fare.
- The model explains approximately 38.8% of the variation in Fare.
- Fare contains several high-value outliers.
- Additional features may improve prediction accuracy.

## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib