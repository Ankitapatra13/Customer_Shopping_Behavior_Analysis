# Customer Shopping Behavior Analysis
This end-to-end project involved importing a Kaggle dataset into Jupyter Notebook for feature engineering and cleaning, then exporting to CSV. Key business queries were answered using MySQL, followed by an interactive Power BI dashboard and final business recommendations.

### 1. Project Overview
 * This project analyzes customer shopping behavior using 3900 transactions across various product categories . The goal is to uncover insights and guide strategic business decisions .

### 2. Dataset Summary
-	Rows : 3900
-	Columns : 18
-	Key Features  :   
•	Customer demographics (customer_id, age, gender, location, subscription_status,  age_group) 
•	Purchase details (item_purchased, category, purchase_amount, color, season)
•	Shopping behavior (review_rating, shipping_type, discount_applied, previous_purchases, payment_method, frequency_of_purchases, purchase_frequency_days)

### 3.	Exploratory Data Analysis Using Python 
•	Data Loading : Imported the dataset using pandas in jupyter lab . 
•	Initial Exploration : Used df.info() to check the overall structure, df.isnull().sum() to check if null values are present, df.head() to see the first 5 rows of the dataset and df.describe(include=”all”) for summary statistics.
•	Column Standardization : Renamed columns to snake case for better readability .
•	Feature Engineering : 
o	Created age_group column by binning customer ages.
o	Created purchase_frequency_days column from frequency_of_purchases .
•	Data Consistency Check : Verified if discount_applied and promo_code_used were redundant ; dropped promo_code_used . 
•	DataFrame To csv file Conversion : Exported the data frame to “Customer Shopping Behaviour Dataset.csv"


### 4. Interactive Power BI Dashboard Design
* Connected Power BI directly to the processed dataset/database.
* Modelled relationships and defined key DAX measures for core metrics.
* Designed an interactive multi-tab layout featuring dynamic slicers, visual hierarchy, and drill-through capabilities.

### 5. Final Reporting & Stakeholder Presentation
* Compiled detailed analytical findings into a structured business report.
* Leveraged Gamma AI to build an executive presentation deck summarizing findings and strategic recommendations.
---
## 📈 Dashboard & Key Insights

### Power BI Dashboard Overview
> *Note: Embed high-resolution screenshots of your Power BI dashboard tabs here.*

```markdown
![Dashboard Preview](path/to/dashboard_screenshot.png)
