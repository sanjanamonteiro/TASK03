# TASK03
# Linear Regression Task

This project demonstrates simple and multiple linear regression using Scikit-learn, Pandas, and Matplotlib.

## Objective

- Understand and implement simple and multiple linear regression.
- Evaluate model performance using MAE, MSE, and R².
- Visualize the regression results.

## Dataset

The script uses the Boston Housing dataset (built-in with scikit-learn) as an example. You can replace it with your own dataset by modifying the data import section.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

## How to Run

1. Clone this repository or download the script.
2. Install required libraries if not already installed:
   ```
   pip install pandas numpy matplotlib scikit-learn
   ```
3. Run the script:
   ```
   python linear_regression_task3.py
   ```

## Script Details

- **Simple Linear Regression:** Uses only one feature (e.g., average number of rooms) to predict the target.
- **Multiple Linear Regression:** Uses all available features in the dataset.
- Both models are evaluated using:
  - **MAE:** Mean Absolute Error
  - **MSE:** Mean Squared Error
  - **R²:** Coefficient of determination

- The regression line for simple linear regression is plotted for visualization.

## Interpreting Results

- **Intercept and Coefficient(s):** Show how the features influence the predicted value.
- **MAE, MSE:** Lower values indicate better model performance.
- **R²:** Indicates the proportion of variance explained by the model (closer to 1 is better).

## Customization

To use your own dataset:
1. Replace the `load_boston()` part in the script with your own CSV import using `pd.read_csv('yourfile.csv')`.
2. Adjust the feature columns as needed.

## License

This project is for educational purposes.
