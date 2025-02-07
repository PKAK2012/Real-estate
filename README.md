# Real-estate

This dataset is consist of land sale price based on various feature and its include columns are
Prt_Id, Area, Int_Sqft, Date_Sale, Dist_Mainroad, N_Bedroom, N_Bathroom, N_Room, Sale_Cond, Park_Facil, Date_Build, Buildtype, Utility_Avail, Street, Mzzone, Qs_Rooms, Qs_Bathroom, Qs_Bedroom, Qs_Overall, Reg_Fee, Commis, Sales_Price

**Objective:**
The objective of this dataset is to analyze property sales data to understand key factors affecting property prices.

**Column Description:**

**Independent Variables (Features)**
Prt_Id – Unique property ID
Area – Location of the property
Int_Sqft – Interior square footage
Date_Sale – Date of sale
Dist_Mainroad – Distance from the main road
N_Bedroom – Number of bedrooms
N_Bathroom – Number of bathrooms
N_Room – Total number of rooms
Sale_Cond – Condition of the sale (e.g., Family, AbNormal, Partial)
Park_Facil – Availability of parking facility (Yes/No)
Date_Build – Year of construction
Buildtype – Type of property (Commercial, House, Others)
Utility_Avail – Utility availability (Sewage, Electricity, Water)
Street – Type of street access (Gravel, Paved, No Access)
Mzzone – Municipal zone classification
Qs_Rooms, Qs_Bathroom, Qs_Bedroom, Qs_Overall – Quality scores of various aspects of the property

**Target Variables (Dependent Variables)**
Sales_Price – The final selling price of the property (Primary Target)
Commis (Commission Fee) – Fee charged on the transaction (Depends on Sales_Price)
Reg_Fee (Registration Fee) – Government fee for property registration (Depends on Sales_Price)


**Machine Learning Approach:**
In this dataset we can consider three columns are target varible(Sales_price,Commis,Reg_fee)
Sales_Price is the primary target variable because it depends on multiple independent features like area, square footage, number of rooms, and quality scores.
Commis (Commission Fee) depends on Sales_Price, making it a secondary target variable in a multi-output regression scenario.
Reg_Fee (Registration Fee) also depends on Sales_Price, behaving similarly to Commis as a dependent variable.

Since the dataset involves predicting continuous values, we classify the problem as:

Supervised Learning – We have labeled output (Sales_Price, Commis, Reg_Fee).
Regression Problem – Since the target variables are continuous.

**Conclusion**
This dataset serves as a great resource for real estate price prediction and understanding property valuation trends. By applying regression techniques, we can build models to estimate prices, helping buyers, sellers, and investors make informed decisions.

