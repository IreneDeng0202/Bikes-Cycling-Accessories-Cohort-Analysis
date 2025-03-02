# 1. Bikes Cycling Accessories Cohort Analysis Project 
This project utilizes Python to perform comprehensive data analysis on transaction and customer data from the Bikes & Cycling Accessories Organization. The primary focus is to explore the data, conduct cohort and retention rate analysis, and integrate customer demographics for deeper insights into purchasing behaviors.

# 2. Data Description
- **Data Description**
This project uses three main datasets detailing transactions, customer demographics and customer address from the Bikes & Cycling Accessories Organization:

- **Transactions Data**
transaction_id; product_id; customer_id; transaction_date; online_order; order_status; brand; product_line; product_class; product_size; list_price; standard_cost; product_first_sold_date: 
- **Customer Demographic Data**
customer_id; name; gender; past_3_years_bike_related_purchases; DOB; age; job_title; job_industry_category; wealth_segment;deceased_indicator; owns_car; tenure: 
- **Customer Address Data**
customer_id;address; postcode; state; country; property_valuation

# 3. Analyses Performed
### Data Cleaning and EDA:
Initial cleaning and exploratory data analysis  on transaction data.
Data cleansing and basic EDA on customer data.

### Cohort Analysis:
Cohort analysis to explore retention rates over different periods.
Heatmaps to visualize retention trends.
Product attribution analysis for declining cohorts, examining how different brands influence customer retention.

### RFM Analysis:
RFM analysis and RFM Scores by customer demographics (gender, age, job industry).
Visualization of RFM segments using pie charts and bar plots.

### Brand Sales Performance:
Analysis of brand performance within the product lines.
Heatmaps to display sales performance.

### Geographic Purchase Patterns:
Examination of customer buying patterns by state.
Visualization of total sales and brand sales proportion by state using pie charts.
