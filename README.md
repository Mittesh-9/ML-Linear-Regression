# Linear Regression Model

This project demonstrates how to build and evaluate a simple Linear Regression model. The notebook walks through the process of loading data, building a model, and visualizing the results.

## Project Summary

The main objective of this project is to build a linear regression model to predict a numerical target variable based on a single feature. The notebook provides step-by-step instructions for:
- Loading and understanding the dataset.
- Performing basic exploratory data analysis (EDA).
- Fitting a linear regression model.
- Visualizing the model's predictions against the actual data.
- Evaluating the model's performance using metrics like R-squared and Mean Squared Error.

## Prerequisites

To run the notebook successfully, you'll need the following Python packages:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`

You can install these dependencies using `pip`:

`pip install numpy pandas matplotlib seaborn scikit-learn statsmodels`

Or if you have already cloned the repository just run 

`pip install -r requirements.txt`

## Outputs

Here are visualizations and results you can expect from this project:

- **Scatter plot with the regression line**: Displays the data points along with the best-fit line showing the relationship between the independent variable (X) and the dependent variable (y).
- **Performance metrics**:
```
                                     OLS Regression Results                                
=======================================================================================
Dep. Variable:         Weight(Pounds)   R-squared (uncentered):                   0.002
Model:                            OLS   Adj. R-squared (uncentered):              0.002
Method:                 Least Squares   F-statistic:                              35.83
Date:                Wed, 02 Oct 2024   Prob (F-statistic):                    2.20e-09
Time:                        16:50:44   Log-Likelihood:                     -1.0967e+05
No. Observations:               17500   AIC:                                  2.193e+05
Df Residuals:                   17499   BIC:                                  2.193e+05
Df Model:                           1                                                  
Covariance Type:            nonrobust                                                  
==============================================================================
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
x1             5.7673      0.964      5.985      0.000       3.879       7.656
==============================================================================
Omnibus:                       13.447   Durbin-Watson:                   0.012
Prob(Omnibus):                  0.001   Jarque-Bera (JB):               11.931
Skew:                           0.000   Prob(JB):                      0.00257
Kurtosis:                       2.872   Cond. No.                         1.00
==============================================================================

Notes:
[1] R² is computed without centering (uncentered) since the model does not contain a constant.
[2] Standard Errors assume that the covariance matrix of the errors is correctly specified.
```
Key metrics such as R-squared, Mean Squared Error (MSE), and others will help you understand how well the model is performing.

## Results

The model performs well in explaining the linear relationship between the feature and the target variable, with performance metrics indicating the strength of the model. This example serves as a good starting point for understanding linear regression.
