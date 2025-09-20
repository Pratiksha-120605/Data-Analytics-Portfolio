# Sales-Dashboard

### Dashboard Link : Currently unavailable  

⚠ Due to temporary issues with my Power BI free account, I am unable to publish this report to the Power BI Service.  
Meanwhile, please refer to the *snapshots from Power BI Desktop* attached below.  
The live link will be updated here once the issue is resolved.

## Problem Statement

This dashboard helps the company ElectroHub analyze its overall sales performance. It provides insights into top-performing and underperforming products, sales trends, discount effectiveness, and customer purchase behavior. By identifying profitable products, high-discount categories, and sales by city, the company can make data-driven decisions to boost sales and improve profitability.

It also highlights the relationship between sales and profit and allows comparison of sales, profit, and quantity across different time periods. Since some products generate high sales but low profit (due to heavy discounts), this dashboard helps in identifying such cases and optimizing pricing strategies.


### Steps followed 

Step 1 : Load sales dataset into Power BI Desktop.

Step 2 : Open Power Query editor & check column quality, distribution, and profile for nulls/errors.

Step 3 : Clean dataset (handle null values, correct data types, remove duplicates if any).

Step 4 : Created multiple report pages for Overview, Top/Bottom 5 analysis, Trends, Comparisons, and Order Details.

Step 5 : Designed KPIs using card visuals for Total Sales, Total Profit, Total Orders, Net Sales, and Average Discount.

Step 6 : Created following visuals:
(a) Bar/Column charts – Top & Bottom 5 Products by Sales, Profit, and Quantity.
(b) Line/Area charts – Sales Trends (Daily, Monthly, Quarterly, Annually).
(c) Scatter Plot – Relationship between Sales & Profit.
(d) Comparison charts – Sales/Profit/Quantity across two selected time periods.
(e) Donut/Pie charts – Average Discount across categories.
(f) Map – Sales by different cities.
(g) Table – Detailed order information (Sales, Profit, Discount, Net Sales, etc.) with filters.

Step 7 : Added slicers for filtering data based on Product, Date, Customer ID, and Promotion Categories.

Step 8 : Created calculated columns and measures using DAX, e.g.:

Total Orders = COUNT([Order ID])

Total Sales = SUM([Sales])

Total Profit = SUM([Profit])

Avg Discount = AVERAGE([Discount])

Step 9 : Finalized report design by adding company name, logo, and theme.

Step 10 : Published report to Power BI Service & pinned visuals to create a single-page live dashboard.
        

# Snapshot of Dashboard (Power BI Service)

** Currently unavailable **
 
 # Report Snapshot (Power BI DESKTOP)

 

# Insights

A multi-page report was created on Power BI Desktop & later consolidated into a single-page dashboard in Power BI Service.

Following inferences can be drawn from the dashboard;

[1] Overall KPIs

Total Sales = [value]

Total Profit = [value]

Total Orders = [value]

Average Discount = [value]%

[2] Top/Bottom Products

Top 5 products by Sales = [list]

Bottom 5 products by Sales = [list]

Top 5 products by Profit = [list]

Bottom 5 products by Profit = [list]

[3] Sales Trends

Highest sales recorded in [month/quarter/year].

Lowest sales recorded in [month/quarter/year].

Seasonal/quarterly trends observed with peaks in [period].

[4] Sales vs Profit Relationship

Positive correlation between Sales & Profit overall.

Some products showed high sales but negative/low profit due to heavy discounts.

[5] Discount Insights

Average discount offered = [value]%.

[Category] had the maximum average discount.

Heavy discounting impacted profit margins for certain products.

[6] Sales by City

City with highest sales = [city].

City with lowest sales = [city].
