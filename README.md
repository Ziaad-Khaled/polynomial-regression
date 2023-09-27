# Polynomial Regression Project

## Overview

Welcome to the Polynomial Regression project! In this project, you will work with a dataset related to air quality and implement polynomial regression techniques to predict the NO2 output. The following tasks outline the project's objectives:

## Tasks

1. **Dataset Introduction**

   - Start by familiarizing yourself with the dataset. You can find detailed information about the data [here](https://archive.ics.uci.edu/ml/datasets/Air+Quality).

2. **Data Preprocessing**

   - Since this dataset contains multiple output labels, focus on the NO2 output for this assignment. Remove any other output variables.

3. **Handling Missing Data**

   - Implement strategies to handle missing data within the dataset.

4. **Date Feature Transformation**

   - Replace the date feature with three separate features: Day, Month, and Year.

5. **Time Feature Transformation**

   - Replace the time feature with three separate features: Hours, Minutes, and Seconds.

6. **Feature Scaling**

   - Apply feature scaling techniques to ensure consistent feature magnitudes.

7. **Lasso CV Polynomial Regression**

   - Evaluate polynomial regression with various degrees of Lasso cross-validation.

8. **Best Model Selection**

   - Choose the optimal degree for polynomial regression based on performance metrics. Print errors on the test data, model coefficients, and Lasso parameters.

9. **Ridge CV Polynomial Regression**

   - Repeat steps 4 and 5 using Ridge cross-validation polynomial regression.

10. **ElasticNet CV Polynomial Regression**

    - Repeat steps 4 and 5 using ElasticNet cross-validation polynomial regression.

11. **Model Comparison**

    - Compare the errors obtained from the three regularization techniques and select the best-performing model.

12. **Model Testing**

    - Load the best model and test it on a manually created sample dataset.

## Getting Started

Please refer to the project's main code files and notebooks for detailed implementation and further instructions.

Happy coding!
