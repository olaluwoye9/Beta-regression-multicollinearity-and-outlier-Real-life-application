# Beta Regression Analysis

This repository contains R code for performing Beta Regression analysis using the `betareg` and `robustbetareg` packages. The analysis includes fitting a beta regression model, calculating various shrinkage estimators, and comparing robust beta regression models.

## Dataset

The dataset used in this analysis is `GasolineYield` from the `MASS` package.

## Code Explanation

1. **Data Preparation**:
    - Load the necessary libraries.
    - Load and prepare the `GasolineYield` dataset.

2. **Beta Regression Model**:
    - Fit a beta regression model using the `betareg` package.
    - Extract model coefficients and precision parameters.
    - Calculate the inverse of the covariance matrix and eigenvalues.

3. **Shrinkage Estimators**:
    - Calculate various improved and new shrinkage estimators.
    - Define Liu parameters for the ridge regression.

4. **Ridge Regression Estimators**:
    - Calculate ridge regression estimators.

5. **Robust Beta Regression**:
    - Fit robust beta regression models using the `robustbetareg` package.
    - Extract robust coefficients.

6. **Mean Squared Errors**:
    - Calculate mean squared errors for different models.

7. **Results**:
    - Combine and display results for comparison.

8. **Variance Inflation Factor**:
    - Calculate and display the variance inflation factor.

9. **Correlation Plot**:
    - Plot the correlation matrix.

10. **Diagnostic Plots**:
    - Generate diagnostic plots for the model.

## How to Run the Code

1. Clone this repository.
2. Install the required R packages: `MASS`, `betareg`, `robustbetareg`, `car`, and `corrplot`.
3. Source the R script.

## Dependencies

- R (version >= 3.6.0)
- `MASS` package
- `betareg` package
- `robustbetareg` package
- `car` package
- `corrplot` package

## License

This project is licensed under the MIT License.
