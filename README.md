**Finance, Supply Chain & Market Analytics**

**Overview**

This project focuses on Finance, Supply Chain, and Market Analytics using SQL. The objective is to improve data accessibility, automate repetitive tasks, and enhance data processing efficiency.

**Features**

•	Centralized SQL Database: Streamlines reporting processes and improves data accuracy.
•	Automated Tasks: Uses stored procedures to reduce manual effort by 40%.
•	Optimized SQL Performance: Implements views, window functions, and database triggers for enhanced reporting speed.

**Database Schema**

The project consists of multiple tables that support analytics in finance and supply chain management:

**Dimension Tables**

•	Dim_Customer: Contains customer details (customer_code, customer, platform, channel, market, sub_zone, region).
•	Dim_Product: Stores product-related information (product_code, division, segment, category, product, variant).

**Fact Tables**

•	Fact_Act_Est: Includes sales and forecast data (date, fiscal_year, product_code, customer_code, sold_quantity, forecast_quantity).
•	Fact_Forecast_Monthly: Stores monthly forecast details (date, fiscal_year, product_code, customer_code, forecast_quantity).
•	Fact_Freight_Cost: Contains freight cost data (market, fiscal_year, freight_pct, other_cost_pct).
•	Fact_Gross_Price: Maintains product pricing information (product_code, fiscal_year, gross_price).
•	Fact_Manufacturing_Cost: Holds manufacturing cost data (product_code, cost_year, manufacturing_cost).
•	Fact_Post_Invoice_Deductions: Includes post-invoice deductions (customer_code, product_code, date, discount_pct, other_deduction_pct).
•	Fact_Pre_Invoice_Deductions: Contains pre-invoice discount data (customer_code, fiscal_year, pre_invoice_discount_pct).
•	Fact_Sales_Monthly: Records monthly sales (date, fiscal_year, product_code, customer_code, sold_quantity).

**Key Insights**

•	Supply Chain Metrics: Analyzes sold quantity, forecast quantity, and net error.
•	Finance Analytics: Evaluates gross price, invoice deductions, and freight costs.

**Tools Used**

•	SQL: For data storage, processing, and analytics.

