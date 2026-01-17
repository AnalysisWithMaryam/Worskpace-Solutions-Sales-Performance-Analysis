# 📊 Retail Stock Sales | Revenue, Trends and Insights
Excel Project | Retail Sales Data | From Raw Data to Business Insight.

## Table of Content

* [Project Overview](#project-overview)
* [Tools & Techniques](#tools--techniques)
* [Dataset Overview](#dataset-overview)
* [Data Cleaning Process](#data-cleaning-process)
* [Excel Dashboard](#excel-dashboard)
* [Key Insight](#key-insight)
* [Recommendations](#recommendations)
  
### Project Overview
This Project analyzes retail stock sales data to uncover trends in revenue, regional sales,product performance and profitabilty,
using Microsoft Excel for transformation and visualization. This project transforms data into actionable insight for improved business performance.

### Tools & Techniques
* Excel
* Power Query for data cleaning and transformation
* Pivot table & Chart for analysis
* Calculates columns for KPIs
* Interactive Dashboard for stakeholders Visualization

### Dataset Overview
Columns:
Order ID, Customer Name, Customer ID, Region, Customer Segment, Product Category, 
Product Name, Total price after discount, Order date, Quantity Ordered, Shipping Date

Sample Review
| Customer ID | Customer Name |	Order ID | Customer Segment |	Product Category |
|-----|----------------------|--------|--------------|-------------|
| 3 | 	Bonnie Potter |	88522 |	Corporate |	Office Supplies |
| 5 |	Ronnie Proctor |	90193 |	Home Office |	Furniture |
| 11 |	Marcus Dunlap |	90192 |	Home Office |	Furniture |
| 14 |	Gwendolyn F Tyson |	86838 |	Small Business | Furniture | 

### Data Cleaning Process
* Removed Missing or Invalid Values
* Created new calculated fields Columns
* Total Price before discount = Unit_price * Quantity_Ordered
* Discount Amount= Total_Price before Discount * Discount_Percentage
* Total Price After Discount = Total_Price before Discount – Discount_Amount

### Excel Dashboard
The Excel Dashboard Include the following visual:
* 📈 Monthly Sales Trend
* Sales Performance by Product Category and Region
* 💰 Revenue Achieved vs Target
* Total Orders vs Target
* Interactive Slicer for Customer segment and region comparison.

  <img width="1283" height="529" alt="worsk dd" src="https://github.com/user-attachments/assets/8762d03c-34d1-4fa1-91de-c4b078ebada1" />

  ### Key Insight
* The company met 82% of their order target and 90% of their Revenue target
* The Wesr region consistently generated the highest revenue
>Office Machines generated the highest revenue
* Customers in the corporate world generated the highest revenue 
* Average shipping time is 2 days

### Recommendations
* Shift focus to high margin categories like technology and furniture.
* Apply successful stretegies from the wst to other underperforming areas
