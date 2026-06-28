###### **Residual Analysis**

1. **Predicted Sales and Residual Calculation**

Residuals were calculated using the following formula:

Residual = Actual Monthly Sales − Predicted Monthly Sales

Where:

* **Positive residual** → Actual sales were higher than predicted (the model under-predicted sales).
* **Negative residual** → Actual sales were lower than predicted (the model over-predicted sales).

Predicted sales were obtained from the final regression model for every observation.

2. Records with the Largest Positive Residuals

|Rank|Store|Month|Store Type|Residual|
|-|-|-|-|-:|
|1|STR-1010|Mar-2025|Mall|804,973.37|
|2|STR-1010|Feb-2025|Mall|799,213.44|
|3|STR-1009|Apr-2025|Residential|775,471.15|
|4|STR-1009|Mar-2025|Residential|769,070.39|
|5|STR-1010|Jan-2025|Mall|761,838.80|



**Business Interpretation**

These observations indicate that actual sales were substantially higher than the model predicted.

Possible business reasons include:

* Successful local promotions that were not included in the model.
* Exceptional customer demand during those months.
* Strong store management or customer service.
* Local events or seasonal factors increasing store traffic.
* Other business variables not captured by the regression model.

These stores significantly outperformed expectations.

**3. Records with the Largest Negative Residuals**

|Rank|Store|Month|Store Type|Residual|
|-|-|-|-|-:|
|1|STR-1007|Jan-2025|Mall|-89,140.45|
|2|STR-1003|Jan-2025|Airport|\~0.89|
|3|STR-1003|Feb-2025|Airport|\~0.79|
|4|STR-1003|Mar-2025|Airport|\~0.78|
|5|STR-1006|Mar-2025|Residential|\~1.13|



**Business Interpretation**

Negative residuals indicate that actual sales were below the predicted values.

Possible reasons include:

* Temporary operational disruptions.
* Lower customer demand than expected.
* Stock availability issues.
* Competitive pressure from nearby stores.
* External market conditions not represented in the regression variables.

The model expected stronger performance than what these stores actually achieved.





**4. Overall Residual Interpretation**

Residual analysis helps determine where the regression model performs well and where it struggles.

The results suggest:

* Several observations have very small residuals, indicating accurate predictions.
* A few stores have extremely large residuals, suggesting unusual business circumstances that are not explained by the variables included in the model.
* These observations may be considered potential outliers for further business investigation.


**5. Does the Model Under-Predict or Over-Predict Certain Stores?**

The residual pattern suggests:

* The model under-predicts some Mall and Residential stores, where actual sales greatly exceed predicted sales.
* For a small number of observations, the model slightly over-predicts sales.
* Most observations appear reasonably close to the predicted values, indicating that the regression captures the overall sales trend while still missing some store-specific influences.

Possible additional variables that could improve the model include:

* Local marketing campaigns
* Customer loyalty activity
* Weather conditions
* Competitor promotions
* Special events and festivals
* Store manager performance indicators



**Conclusion**



The residual analysis shows that the final regression model explains much of the variation in monthly sales but cannot fully capture exceptional store performance. Large positive residuals indicate stores performing significantly better than expected, while negative residuals highlight stores that underperformed relative to model predictions. These observations provide valuable opportunities for management to investigate best practices, operational issues, and additional business factors that could further improve future sales forecasting models.

