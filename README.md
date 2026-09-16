# Coffee-Sales-Analysis-Excel-Dashboard
The coffee shop management wants to analyze sales and customer patterns to understand peak demand hours, popular product categories, and store performance across locations to cut wait times, optimize staffing, and boost daily store profits.

# Dataset Used
<a href="https://github.com/Asmi-5077/Coffee-Sales-Analysis-Excel-Dashboard/blob/main/Coffee%20Shop%20Sales.xlsx">Dataset</a>

## Questions ( KPIs) 

-  What is the overall business performance in terms of Total Sales, Total Footfall, Average Bill per Person, and Average Order Size?
-  Which hours of the day generate the highest quantity of orders (Peak Hours)?
-  Which top 5 products generate the maximum sales revenue?
-  What is the revenue percentage share across different product categories?
-  How does sales revenue and footfall vary across different store locations?
-  How are order volumes distributed across different product sizes (Large, Regular, Small, etc.)?
-  How do total order volumes fluctuate across different days of the week?

- Dashboard Interaction <a href="https://github.com/Asmi-5077/Coffee-Sales-Analysis-Excel-Dashboard/blob/main/coffee%20sales%20analysis%20dashboard%20pic.png">View Dashboard</a>

## Process

- Imported raw coffee shop transactional data (~140,000 rows) containing dates, times, product details, quantities, prices, and store locations.
- Cleaned missing values, removed duplicate transaction records, and updated data types for prices, dates, and order quantities.
- Extracted hour integers from timestamps, categorized product sizes, and derived day names and month names for time-series analysis.
- Calculated core business KPIs like Total Sales, Total Footfall, Average Bill per Person, and Average Order per Person.
- Created individual Pivot Tables to analyze sales by category, top 5 products, hourly order volume, location performance, and weekday trends.
- Merged all visual charts and KPI cards into a single cohesive, coffee-themed dashboard layout.
- Applied interactive Month and Day slicers linked across all Pivot Tables and tested all visual filters for dynamic responsiveness.

## Dashboard 

![Uploading hospital emergency dashboard pic.png…](https://github.com/Asmi-5077/Coffee-Sales-Analysis-Excel-Dashboard/blob/main/coffee%20sales%20analysis%20dashboard%20pic.png)


## Project Insight 

- Total sales reached $698,812.33 across 149,116 customer visits, with an average spend of $4.69 per bill.
- Order volume spikes sharply between 8:00 AM and 10:00 AM, reaching over 25,000 units sold during peak hours.
- Barista Espresso generated the highest sales revenue at $91,406.20, followed by Brewed Chai Tea and Hot Chocolate.
- Coffee is the top-selling product category accounting for 39% of total sales, followed by Flavours at 28%.
- Sales revenue and customer footfall are distributed almost equally across all three store locations.
- Customers mostly prefer Regular (31%) and Small (30%) drink sizes over Large sizes (9%).
- Daily order counts stay consistent between 21,000 and 21,700 from Monday through Friday, with a minor dip on Saturdays.

## Conclusion 
- The coffee shop maintains steady weekday footfall and balanced revenue across all three locations, with 8:00 AM–10:00 AM acting as the critical revenue window that demands peak staffing. Coffee and Flavours drive 67% of total sales—led by Barista Espresso—meaning future growth relies on launching targeted afternoon promotions to boost slow hours and upselling customers from Regular to Large sizes.












