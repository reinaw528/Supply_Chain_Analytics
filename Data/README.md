data source: https://www.kaggle.com/code/premakotliya/supply-chain-analytics/notebook?select=retail_store_inventory.csv

# Schema Review

Dataset Size

- 73,100 rows
- 15 columns

Variables

Temporal Variables

- Date

Categorical Variables

- Store_ID
- Product_ID
- Category
- Region
- Weather_Condition
- Seasonality

Numerical Variables

- Inventory Level
- Units Sold
- Units Ordered
- Demand Forecast
- Price
- Discount
- Competitor Pricing

Binary Variables

- Holiday/Promotion


## Schema Review - Observations

• The dataset contains 73,100 observations and 15 variables.

• All columns contain 73,100 non-null entries, indicating that no missing values are present.

• The dataset consists of seven categorical variables, five integer variables, and three floating-point variables.

• The Date column is currently stored as a string and should be converted to datetime format.

• The dataset spans 731 days, covering approximately two years of historical sales records.

• Five stores and twenty products are included in the dataset.

• Each record represents inventory and sales information for a specific product in a particular store on a given date.

• The dataset occupies approximately 8.4 MB of memory and can be processed efficiently on a local machine.
