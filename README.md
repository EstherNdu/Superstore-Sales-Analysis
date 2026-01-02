# Superstore-Sales-Analysis

# Brief Introduction
Behind every sale is a story of customer behavior, pricing decisions, and profitability. This sales performance report explores those stories by analyzing revenue, profit, discounts, customer retention, and product performance over time. The analysis highlights how sales volume does not always translate to profit, how discounts influence margins, and which customers and products truly drive sustainable growth. It showcases the power of data storytelling in turning transactional data into clear, actionable business insights.

# About The Dataset
This project is built on a five-table relational dataset comprising 9,994 order records, 793 customer records, 1,894 product records, 632 location records, and 49 state records. The dataset captures transactional sales data alongside detailed customer, product, and geographic attributes. It provides a strong foundation for analyzing sales performance, profitability, customer behavior, product trends, and regional dynamics.

# Problem Questions
* Which products generated the highest profits?
* How did revenue and profit vary by month?
* How did discount rate affect profit?
* Which region and customer segment generate the highest profits?
* Did the company lose customers across months?
* Which customer segment had the highest number of customers?
* Which product category gave the highest discounts?
* Which products were sold at loss
* Which states had the highest profit and profit margin?
* What are the top 5 cities by orders?

# Tool Used 
  Power Query & Power BI

# Processes 
* Imported the data into Power BI
* Transformed the data using Power Query
* Loaded the data into Power BI for Analysis & Reporting
* Modeled the data
* Created a calendar table
* Created parameters for customer segment and product category
* Used DAX to perform indepth analysis
* Created interactive reports

# Data Modeling
<img width="1634" height="629" alt="Screenshot 2026-01-02 213156" src="https://github.com/user-attachments/assets/723a2ac9-4d97-4383-9520-5a4df7d4c29d" />

# Key Insights
<img width="1013" height="130" alt="Screenshot 2026-01-02 213339" src="https://github.com/user-attachments/assets/15cdc13c-997a-4756-9c1d-34ab5b3bebb7" />

* $2.30M in Total Revenue was generated, representing a 3.8% Month-over-Month (MoM) increase in sales performance.
* $286.4K in Total Profit was realized, reflecting a 3.1% MoM growth in net earnings.
* 12.5% Profit Margin was achieved, representing a 0.7% MoM decrease, indicating rising operational costs or tighter margins.
* Average Sales Value of $458.6 was recorded, with a 0.9% MoM decrease, suggesting a shift toward higher-volume, lower-value transactions.

<img width="1404" height="777" alt="Screenshot 2025-11-02 221117" src="https://github.com/user-attachments/assets/bf9108e4-8653-4619-b00f-00947047d581" />

* The Consumer segment is the primary revenue driver, contributing $1.2M, which is more than the Home Office and Corporate segments combined.
* The Canon image Class 2200 Advanced Copier stands out as the highest profit-generating product, contributing $25K — more than triple the profit of the second-highest product.
* A significant growth trend is visible in the latter half of the year, with revenue peaking in November ($352K) followed by a slight dip in December ($325K).

<img width="1403" height="769" alt="Screenshot 2025-11-02 221318" src="https://github.com/user-attachments/assets/685dd81b-9c74-409b-8c58-248926e94738" />

* $57.2 Profit per Order was recorded for the period.
* 15.62% Average Discount was applied across orders, seeing a slight 0.3% MoM decrease.
* $60.7 Average Price per product was recorded, reflecting a 0.9% MoM decrease.
* Orders with no discount or small discounts (10-30%) drive the highest profit, while discounts above 31% lead to significant profit decreases.
* Profit shows a significant upward trend toward the end of the year, peaking in December.
* West region generated the highest profit (108.4k), followed by East (91.5k) and South (46.7k)

<img width="1397" height="776" alt="Screenshot 2025-11-02 223250" src="https://github.com/user-attachments/assets/004b4c95-bebc-4948-a558-91b122580377" />


* 1,894 Total Products are currently in the catalog, a 0.2% MoM increase.
* $60.7 Average Price per product was recorded, reflecting a 0.9% MoM decrease.
* Technology is the highest-priced category at an average of $120.5, while Office Supplies is the lowest at $31.4.
* Profit Loss: Several products, such as the Cubify CubeX, are currently being sold at a loss, with Cubify CubeX losing $8.9K.

<img width="1406" height="774" alt="Screenshot 2025-11-02 223232" src="https://github.com/user-attachments/assets/d85f01c9-abc9-4203-916e-d5ea850f6d8e" />

* 793 Total Customers were active, showing 0.0% MoM change in the customer base size.
* 49.62% Repeat Customer Rate was achieved, which is a 0.5% MoM increase.
* $2.90K Average Order Value (AOV) per Customer was recorded, a 3.8% MoM increase.
* The Consumer segment accounts for the majority of the customer base at 51.58% (409 customers).
* The Consumer segment is the most significant contributor, accounting for $1.2M (50.56%) of total revenue.
* Although the Consumer segment generates the most revenue, the Corporate segment is highly efficient, contributing 30.74% of revenue from only 29.76% of the total customer base.
* Sean Miller is the highest-grossing customer with $25,043.1 in revenue, though this account currently shows a negative profit margin of -7.9%.
* Tamara Chand and Raymond Buch represent ideal customer profiles, both maintaining profit margins above 46%.

<img width="1404" height="786" alt="Screenshot 2025-11-02 223638" src="https://github.com/user-attachments/assets/48d0a247-12d5-4c06-9366-6b14dd2efceb" />

* The West Region is the highest performing area, generating $725.5K in revenue and $0.11M in profit.
* 38K Units Sold were recorded, showing a 4.8% MoM increase.
* California and New York are the top-performing states by profit, contributing $76K and $74K respectively.
* New York City leads at the local level with 450 orders and $256,368.2 in revenue.
