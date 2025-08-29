# AtliQ Technologies — Sales & Profit Insights Case Study  

## Project Highlights  
- Built an end-to-end BI solution in **Power BI** analyzing sales and profitability (2017–2020).  
- Processed data across **markets, customers, products, and transactions**.  
- Identified **profitability risks** (e.g., –17.2% losses in Bengaluru) and **dependency on Delhi NCR** (~53% of revenue).  
- Delivered **interactive dashboards** and an executive **growth report** highlighting revenue trends, profit margins, and customer concentration.  

---

## Overview  
This project analyzes **AtliQ Technologies’ sales and profit performance (2017–2020)** using **Power BI**.  

The goal was to uncover:  
- Profit drivers and underperforming regions  
- Market & customer dependency risks  
- Revenue distribution across markets and product categories  

and provide actionable recommendations to improve:  
- Profit margins  
- Market diversification  
- Customer mix  
- Operational efficiency  

This project demonstrates **data storytelling, DAX-driven insights, and BI dashboarding** — skills crucial for business data roles.  

---

## Objectives  
- Evaluate **sales and profit performance** across markets, customers, and products.  
- Identify **profitability gaps** (loss-making markets, customer concentration, product categorization issues).  
- Build **DAX measures** for Profit%, Contribution%, YoY Growth, and Revenue.  
- Deliver an **interactive Power BI dashboard** for business stakeholders.  

---

## Data & Model  
The dataset was provided as a **SQL source file** (transactional sales data and supporting dimensions).  

**Data Model:**  
- **sales_transactions** → fact table (cost_price, norm_sales_amt, order_date, profit_margin, etc.)  
- **sales_products** → product metadata (product_code, product_type)  
- **sales_markets** → market metadata (market_code, market_name, zone)  
- **sales_customers** → customer metadata (customer_code, customer_name, customer_type)  
- **sales_date** → calendar table (cy_date, year, month_name)  
- **Profit Target** → benchmark table (Profit Target, Profit Target Value)  
- **Base Measures** → DAX-driven measures (Profit Contribution %, Revenue, Quantity, YoY Growth, etc.)  

---

## Tools & Technologies  
- Power BI (data modeling, dashboards, DAX)  
- SQL (data source, joins, transformations)  
- Excel (data validation, exploration)  

---

## Methodology  
1. **Data Understanding & Cleaning**  
   - Validated dimensions and transactional data.  
   - Checked missing values and integrity of keys across fact/dim tables.  

2. **Data Modeling**  
   - Built a **star schema** with `sales_transactions` as fact and supporting dimension tables.  

3. **DAX Measures & KPIs**  
   - Developed measures for **Profit%, Contribution%, Revenue, Quantity, YoY Growth**.  

4. **Exploratory Analysis**  
   - Identified loss-making regions (Bengaluru, Kanpur).  
   - Studied dependency on Delhi NCR and Mumbai.  
   - Detected product categorization issue due to “(Blank)” entries.  

5. **Dashboard Development**  
   - Built views for executives (high-level KPIs) and analysts (detailed breakdowns).  

6. **Insights & Recommendations**  
   - Converted analysis into strategic recommendations for leadership.  

---

## Metrics & KPIs  

### Core KPIs  
- Revenue (₹984.87M total)  
- Profit (₹24.66M total)  
- Profit % (2.6%)  
- Quantity Sold (2M units)  
- Contribution % by Market, Customer, Product  

### Comparative Metrics  
- Year-over-Year Profit% (2017: 2.3%, 2018: 3.0%, 2019: 3.2%, 2020: 1.5%)  
- Revenue by Market, Zone, and Customer  
- Profit Contribution % by Market  

---

## Key Insights  
1. Market Concentration: Delhi NCR drives ~53% of revenue and 48% of profit contribution.  
2. Underperforming Regions: Bengaluru (–17.2% profit margin), Kanpur (–0.5%), Hyderabad (0.5%).  
3. Profit Concentration: Nearly 70% of profits from Delhi NCR + Mumbai.  
4. Customer Dependency: Top 5 customers contribute the bulk of revenue (Electricalsara Stores alone = 42%).  
5. Product Data Quality Issue: Large portion of sales tagged as “(Blank)” product category.  
6. YoY Trend: Peak profitability in 2019 (3.2%) followed by decline in 2020 (1.5%).  

---

## Recommendations  
- Fix data gaps by resolving the “(Blank)” product category issue for cleaner insights.  
- Diversify markets and customer base to reduce dependency on Delhi NCR and a handful of top accounts.  
- Address losses in underperforming regions like Bengaluru and Kanpur by reviewing costs and pricing.  
- Enhance profitability using AI-driven forecasting, dynamic pricing, and operational automation.  

---

## Deliverables  
- Power BI Dashboard (.pbix)  
- Atliq Growth Report (2017–2020)  
- Data Model (PNG)  
- Dashboard Screenshots (JPG)  
- Metadata (Excel)  
- SQL Source File (generalized, not included here)  

---

## How to Run the Project  
1. Clone this repository.  
2. Open `powerbi/Atliq_Sales_Insights.pbix` in Power BI Desktop.  
3. Connect to SQL/CSV data sources in `/data`.  
4. Refresh data and interact with slicers (year, market, customer, product).  

---

## Learnings  
- Built **end-to-end BI workflow**: data → model → insights → recommendations.  
- Practiced **DAX calculations, YoY analysis, and contribution analysis**.  
- Strengthened skills in **business storytelling with data**.  

---

## Author  
**Ritik Kaithwar**  
