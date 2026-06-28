# prakharsrivastava_bitsom_ba_2511927_part3_regression_insights

# Regression-Based Business Insights & Model Interpretation

## Business Problem Summary

A retail chain aims to understand which business factors are most strongly associated with monthly store sales. Management wants data-driven insights to support strategic decisions such as increasing marketing investment, optimizing inventory levels, adjusting discount strategies, reallocating staff, and prioritizing high-performing store types or regions.

This project applies regression analysis to quantify the relationship between monthly sales and several operational and business variables, enabling evidence-based decision-making.

---

# Dataset Description

The dataset contains monthly sales information for multiple retail stores. Each observation represents a store's performance during a specific month.

The dataset includes business-related variables such as:

* Monthly Sales (target variable)
* Marketing Spend
* Inventory Availability
* Discount Percentage
* Number of Staff
* Store Type
* Region
* Other operational attributes

The data was cleaned and prepared before performing regression analysis.

---

# Dependent and Independent Variables

## Dependent Variable

**Monthly Sales**

Monthly Sales is the response (target) variable that the regression model attempts to predict.

## Independent Variables

The final regression model evaluates the impact of several explanatory variables, including:

* Marketing Spend
* Inventory Availability
* Discount Percentage
* Number of Staff
* Store Type (Dummy Variables)
* Region (Dummy Variables)

These variables were selected because they represent business decisions that management can influence.

---

# Regression Approach

The analysis followed a step-by-step regression modeling process.

### 1. Simple Linear Regression

Each independent variable was analyzed individually to measure its relationship with Monthly Sales.

### 2. Multiple Linear Regression

Multiple business variables were combined into a single regression model to estimate their simultaneous effect on Monthly Sales.

### 3. Model Diagnostics

The following were evaluated:

* R² and Adjusted R²
* Significance of coefficients (p-values)
* Residual analysis
* Prediction accuracy
* Business interpretability

---

# Dummy Variable Approach

Categorical variables such as Store Type and Region cannot be directly used in regression.

Dummy variables were created using one category as the reference group.

For example:

### Store Type

Reference Category:

* Mall Store

Dummy Variables:

* Airport Store
* Residential Store
* Downtown Store

### Region

Reference Category:

* North

Dummy variables estimate how each category differs from the reference category while avoiding the dummy variable trap.

---

# Model Comparison Summary

Several regression models were compared using statistical performance and business relevance.

| Model                                    | Variables Included                  | Strengths                                               | Limitations                          |
| ---------------------------------------- | ----------------------------------- | ------------------------------------------------------- | ------------------------------------ |
| Simple Regression                        | One predictor                       | Easy to interpret                                       | Ignores interaction among variables  |
| Multiple Regression                      | Continuous predictors               | Higher explanatory power                                | Does not capture categorical effects |
| Multiple Regression with Dummy Variables | Continuous + categorical predictors | Highest predictive accuracy and business interpretation | Slightly more complex                |

The comparison showed that including both continuous and categorical variables improved the model's explanatory power.

---

# Final Model Selected

The final selected model is the **Multiple Linear Regression model with Dummy Variables**.

This model was selected because it:

* Produced the highest Adjusted R²
* Explained the greatest variation in Monthly Sales
* Included statistically significant business drivers
* Captured differences across store types and regions
* Provided the most actionable business insights

---

# Business Recommendation

Based on the regression analysis:

* Increase marketing investment in stores where marketing spend has a strong positive relationship with sales.
* Maintain high inventory availability to reduce lost sales opportunities.
* Use discounts strategically rather than excessively, ensuring profitability while attracting customers.
* Allocate staffing according to expected customer demand.
* Prioritize investment in store types and regions that consistently outperform the reference categories.
* Investigate stores with unusually large residuals to identify best practices or operational issues not captured by the model.

These recommendations support more effective resource allocation and improved sales performance.

---

# Assumptions and Limitations

## Assumptions

The regression analysis assumes:

* Linear relationships between predictors and sales.
* Independent observations.
* Constant variance of residuals (homoscedasticity).
* Normally distributed residuals.
* Limited multicollinearity among independent variables.

## Limitations

* The model only explains variation using the available variables.
* External influences such as local competition, economic conditions, holidays, weather, and customer preferences were not included.
* Regression identifies statistical associations rather than proving causation.
* Extreme observations (outliers) may affect coefficient estimates and prediction accuracy.

Future models could be improved by incorporating additional operational and market-related variables.

---

# Screenshots Included

The project submission includes screenshots demonstrating:

* Regression output tables
* Model comparison results
* Dummy variable creation
* Predicted vs. Actual Sales
* Residual analysis
* Final regression model
* Excel regression outputs and supporting calculations

These screenshots provide evidence of the analytical process and support the conclusions presented in this project.
