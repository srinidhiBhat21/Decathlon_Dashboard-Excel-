## Dataset — Decathlon Synthetic Retail Transactions
Overview
This folder contains the synthetic retail transaction dataset used in the Decathlon Sales & Customer Analytics project.

File: Decathlon_Synthetic_Data_30000.xlsx
Records: 30,000 order rows
Fields: 39 columns
Period represented: 2024–2026
Format: Excel workbook (.xlsx)
Important: This is synthetic data for learning and portfolio demonstration. It is not official Decathlon data and should not be used to make claims about the company's actual performance.

Data fields
Field	Description
Order_ID	
Order_Date	
Order_Time
Customer_ID	
Customer_Name	
Gender	
Age	
Age_Group
City, State	
Product_ID	
Product_Name
Product_Category
Brand	
Sport_Type	
Quantity	
Unit_Price	
Discount_Percent	
Discount_Amount
Sales_Amount
Final_Amount	
Cost_Price	
Profit	
Store_ID	
Store_Name
Sales_Channel
Payment_Method
Salesperson	
Delivery_Type	
Delivery_Days	
Customer_Rating	
Return_Status	
Return_Reason	
Promotion_Campaign	
Quarter
Month
Year	

Suggested analysis questions
- How do sales and order counts change year over year?
- Which sports types contribute the most sales and orders?
- Which product categories generate the most revenue?
- What is the monthly sales pattern?
- How do average order values compare across years?
- How do sales differ by gender, membership type, customer segment, channel, or geography?
- What patterns appear in ratings, returns, delivery times, and promotions?
- How is customer retention defined and how does it change over time?

Data preparation and validation suggestions
Before extending the analysis, consider checking:
1. Duplicate Order_ID values.
2. Missing values in identifiers, dates, and key numeric fields.
3. Whether Order_Date, Month, Quarter, and Year are consistent.
4. Whether Sales_Amount, Discount_Amount, Final_Amount, Cost_Price, and Profit reconcile under the dataset's business rules.
5. Whether customer IDs repeat across multiple orders as expected.
6. Whether return statuses and return reasons are logically consistent.
7. Whether the definition of a customer and the retention formula match the dashboard's intended meaning.

Use with the dashboard
The dataset is used by the Excel dashboard to build PivotTables, KPI summaries, and charts. Keep the source column names stable if you plan to refresh or reconnect the workbook to this file.
Responsible use
This dataset is synthetic and intended for educational analysis, portfolio projects, and dashboard demonstrations only. Do not present its values as real-world company results.
