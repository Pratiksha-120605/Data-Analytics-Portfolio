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
 <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/413938c4-9fe8-4ed7-9ed9-a60683164301" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/4f3400ca-2365-44af-8f1e-5dc2ea678332" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/0d4d12e9-67f1-4683-9353-009b07681cd1" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/8298ee1a-49d6-47cc-8cae-0ade54a75d4f" />
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/bfdc93c5-b5f3-43ae-806e-dd3dce66d144" />

 
# Insights  

A multi-page report was created on Power BI Desktop & later consolidated into a single-page dashboard in Power BI Service.  

Following inferences can be drawn from the dashboard;  

### [1] Overall KPIs  

- **Total Sales** = 94M – 107M (across periods compared)  
- **Total Profit** = 9.4M – 10.7M (across periods compared)  
- **Total Orders** = 5.4K – 6.3K (across periods compared)  
- **Average Discount** = [value pending from data]%  

---

### [2] Top/Bottom Products  

- **Top 5 Products by Sales**:  
  - Apple iPhone 14 (21M)  
  - Apple MacBook Air (19M)  
  - Sony Bravia 55” TV (19M)  
  - Samsung Galaxy S21 (15M)  
  - HP Pavilion Laptop (14M)  

- **Bottom 5 Products by Sales**:  
  - Tupperware Lunch Box (0.26M)  
  - L’Oreal Shampoo (0.17M)  
  - Nivea Body Lotion (0.08M)  
  - Dove Soap Pack (0.08M)  
  - Colgate Toothpaste (0.02M)  

- **Top 5 Products by Profit**:  
  - Apple iPhone 14 (2.1M)  
  - Apple MacBook Air (1.9M)  
  - Sony Bravia 55” TV (1.9M)  
  - Samsung Galaxy S21 (1.5M)  
  - HP Pavilion Laptop (1.4M)  

- **Bottom 5 Products by Profit**:  
  - Tupperware Lunch Box (26K)  
  - L’Oreal Shampoo (17K)  
  - Nivea Body Lotion (8K)  
  - Dove Soap Pack (8K)  
  - Colgate Toothpaste (2K)  

---

### [3] Sales Trends  

- **Highest sales recorded**: Second selected period (107M).  
- **Lowest sales recorded**: First selected period (94M).  
- **Observation**: Clear growth in both Sales (+13M), Profit (+1.3M), and Quantity Sold (+900) between the two selected periods.  

---

### [4] Sales vs Profit Relationship  

- Strong **positive correlation** between Sales & Profit (top products like iPhone 14 and MacBook Air drive both).  
- Some **low-value products** (Tupperware, soaps, lotions) contribute sales but generate **minimal profit**.  

---

### [5] Discount Insights  

- Average discount percentage not shown in the shared snapshots — needs to be pulled from the **Discount KPI/visual** in the dashboard.  
- Likely trend: **High-discount products fall in Bottom 5 Profit category**, affecting overall profitability.  


### [6] Sales by City  

- **Highest Sales City** = Mumbai (~9.83M Net Sales)  
- **Lowest Sales City** = Bangalore (~1.54M Net Sales)  
