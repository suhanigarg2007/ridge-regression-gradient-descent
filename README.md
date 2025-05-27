# My Learnings on Ridge Regression Using Gradient Descent

This is my work that explores Ridge Regression implemented from scratch using Gradient Descent and compares the results with scikit-learn's Ridge regression model.

## Ridge Regression Results Comparison

### Custom Implementation (Gradient Descent)
- **R² Score:** 0.4625  
- **Coefficients:**  
  `[  34.52, -290.84,  482.40,  368.07, -852.45,  501.59,  180.11,  270.76,  759.74,  37.49]`  
- **Final Cost (Loss):** 151.10

### Scikit-learn Ridge Regression

- **Before Training:**  
  - R² Score: 0.4460  
  - Coefficients:  
    `[  49.34, -147.96,  359.80,  266.20,   -3.02,  -55.85, -167.78,  137.73,  323.26, 101.99]`  
  - Cost: 164.60

- **After Training:**  
  - R² Score and coefficients closely match the custom implementation, confirming the correctness of the gradient descent method.

## Summary

- The custom gradient descent approach achieved an R² score slightly better than the initial sklearn model.
- After training, both methods converge to very similar results.
- This validates the correctness and effectiveness of the custom Ridge Regression implementation.
- The project provided valuable insights into gradient descent optimization and regularized linear regression.

