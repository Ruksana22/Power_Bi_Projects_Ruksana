
### **Microsoft Power BI Capstone Project: Tawilind Traders Problem Statement**
---

### **Problem Statement:**

Tawilind Traders, a growing e-commerce company that specializes in electronics, home goods, and fashion, has been facing challenges in optimizing its sales operations, inventory management, and customer engagement strategies. Despite a steady increase in sales, the company has observed several inefficiencies and missed opportunities, particularly in the following areas:

1. **Sales Optimization**: 
   - Revenue growth is inconsistent across different regions, with certain product categories underperforming, while others are overstocked.
   - Seasonal spikes in sales (e.g., during Black Friday and holidays) lead to stockouts of high-demand products, resulting in missed sales opportunities.

2. **Inventory Management**:
   - The company faces frequent stockouts in high-demand categories, such as electronics, during peak seasons.
   - Certain slow-moving inventory items (like furniture and home goods) sit in stock for too long, leading to higher holding costs.

3. **Customer Engagement**:
   - There is no clear insight into customer segments that drive the most revenue, leading to under-optimized marketing strategies.
   - The company lacks a clear view of how different customer demographics (age, region, buying habits) are influencing sales and revenue.

4. **Profit Margins**:
   - While overall revenue is increasing, profit margins are shrinking due to increased costs of goods sold (COGS), especially for electronics.
   - Promotional discounting during peak seasons is affecting net profitability.

---

### **Goal of the Project**:

The goal of this Microsoft Power BI Capstone Project is to provide actionable insights to Tawilind Traders by analyzing its sales, inventory, customer, and profit data. The analysis will help the company:

- **Optimize product sales** by identifying high-performing product categories and underperforming regions.
- **Improve inventory management** to prevent stockouts and optimize stock levels across different product categories.
- **Enhance customer engagement strategies** by identifying key customer segments and analyzing their purchasing behavior.
- **Increase profitability** by analyzing the relationship between sales, costs, and promotional discounts.

---

### **Key Objectives**:

1. **Sales and Revenue Analysis**: 
   - Track total sales over time (monthly, quarterly, yearly) to identify growth trends and seasonal peaks.
   - Break down sales by region, product category, and customer demographic.

2. **Inventory Management Insights**:
   - Analyze stock levels and identify products frequently out of stock, especially during high-demand periods.
   - Evaluate inventory turnover rates across different product categories and highlight slow-moving inventory.

3. **Customer Behavior Analysis**:
   - Segment customers based on purchasing patterns (e.g., high-value customers, frequent shoppers).
   - Examine demographic data (age, region, etc.) to understand which groups are contributing most to sales and profitability.

4. **Profit Margin Analysis**:
   - Evaluate the impact of promotional discounts on profitability.
   - Identify high-margin product categories and explore ways to improve overall profitability.

---

### **Expected Outcomes**:

- **Sales Insights**: A better understanding of which product categories perform best and which regions require more attention.
- **Inventory Insights**: Reduced stockouts and better inventory management, especially during seasonal peaks.
- **Customer Insights**: Targeted marketing campaigns based on customer segmentation and buying patterns.
- **Profitability Improvements**: Recommendations for optimizing promotions and reducing costs to protect profit margins.

---

### **Key Deliverables**:

1. **Power BI Dashboard**:
   - **KPI Cards**: Revenue, sales, profit margin.
   - **Sales Trends**: Line graphs showing sales over time, segmented by region, product category, and customer type.
   - **Inventory Insights**: Heatmap or bar charts showing stock levels, stockouts, and inventory turnover.
   - **Customer Segmentation**: Visuals displaying customer demographics and purchasing behavior.
   - **Profit Margin Analysis**: Scatter plots and bar charts analyzing the relationship between sales and cost of goods sold.

2. **Data Model**:
   - Cleaned and pre-processed data integrated into Power BI with appropriate relationships and DAX measures for efficient analysis.

3. **Actionable Recommendations**:
   - Sales optimization strategies (e.g., focusing on high-margin products, expanding in underperforming regions).
   - Inventory optimization tips (e.g., reducing slow-moving inventory, ensuring stock availability for high-demand items).
   - Customer engagement strategies (e.g., targeting specific demographics for marketing).
   - Profitability improvements (e.g., optimizing discount strategies, focusing on high-margin products).

---

### **Tools and Technologies**:
- **Microsoft Power BI** for data visualization, analysis, and reporting.
- **Power Query** for data cleaning and transformation.
- **DAX (Data Analysis Expressions)** for creating custom metrics and KPIs.
- **Power BI Desktop** for creating the reports and dashboards.

---

### **Target Audience**:
- **Tawilind Traders' Management Team**: To help make data-driven decisions regarding product strategy, inventory management, and customer targeting.
- **Marketing Team**: To develop targeted marketing campaigns based on customer behavior and preferences.
- **Inventory and Operations Team**: To optimize stock levels and prevent inventory shortages.

---

By using **Microsoft Power BI**, Tawilind Traders can gain clear insights into sales performance, customer behavior, and inventory management, ultimately improving its bottom line. The project will provide actionable insights for better decision-making and optimization of business operations.

---
# Tools
Tools used for Data Cleaning, Data Analysis and Report generation:

    •	Excel
    •	PowerBI
    •	PowerBI 
    
# WorkFlow of this project:
Here's a comprehensive outline for this Data Analytics Power BI Project including:

    - Exploratory Data Analysis (EDA)
    - Insights and Findings
    - Trends
    - Recommendations
    - Conclusion


# EDA Steps in Power BI:

## Dataset Overview:
- **Columns**:
  - **Date** (transaction date)
  - **Product Category** (e.g., electronics, furniture, etc.)
  - **Sales Volume**
  - **Revenue**
  - **Profit Margin**
  - **Customer Demographics** (e.g., region, age group)
  - **Inventory Levels**
  - **Cost of Goods Sold (COGS)**

- **Cleaning Data**: 
  - Identify and address missing values (e.g., missing sales data for certain periods).
  - Convert data types (e.g., Date fields to date format, numeric fields to currency).
  - Normalize columns (e.g., product categories, regions, customer age group).

# Data Cleaning
In the initial data preparation phase, I performed the following tasks:

    •	Data loading and inspection,
    •	Changing data types,
    •	Optimizing the dataset by removing unnecessary and duplicate columns,
    •	Standardizing abbreviations used in the dataset,
    •	Handling missing values,
    •	Data cleaning and formatting

# Data Modeling
 
  - Create relationships between tables (e.g., Sales, Inventory, Customer Data).
  - Use DAX (Data Analysis Expressions) to create calculated columns (e.g., `Profit = Revenue - COGS`).


![alt text](Images/Data_model.png)

# Dashboard Design and Creation

Sales Overview
![alt text](<Images/Sales overview.png>)

Profit Overview
![alt text](Images/Profit_overview.png)


- **Visualizing Trends**: 
  - **Line charts** for revenue and sales trends over time.
  - **Bar charts** to compare sales by product category.
  - **Scatter plots** for understanding the relationship between sales and inventory levels.
  - **Slicers** for filtering by region, customer age, or product category.

---
 # Key Findings

#### **Sales & Revenue Analysis**:
- **Highest Revenue**: Product Category **Electronics** consistently generates the highest revenue, especially in Q4.
- **Top Customers**: A small percentage of customers (about 20%) generate 60% of the revenue.
- **Geography**: Sales in **North America** outpace all other regions, with **Europe** showing consistent growth.
  
#### **Inventory & Stocking**:
- **Inventory Shortage**: Some high-demand products (e.g., Smartphones) experience frequent stockouts, affecting sales.
- **Inventory Aging**: Certain product categories (e.g., furniture) have a slow turnover, leading to higher inventory holding costs.
  
#### **Profit Margins**:
- **Profit Margins by Product Category**: **Electronics** have the highest profit margin but are also subject to frequent price fluctuations.
- **Profit Margin Decline**: In the last quarter, profit margins dropped by 5%, mostly due to increased COGS and promotional discounts.
---

# Trends

#### **Sales Trends**:
- **Seasonal Spikes**: Sales experience significant spikes in **November and December**, likely due to Black Friday and holiday season promotions.
- **Year-over-Year Growth**: The company has shown a steady 12% year-over-year growth in revenue, with consistent demand in **electronics**.
  
#### **Inventory Trends**:
- **Stockouts in High-Demand Categories**: Products in **electronics and gadgets** frequently run out of stock, especially during sales events.
- **Slow-moving Inventory**: Certain **furniture and home goods** are sitting in stock for extended periods, impacting profitability.
  
#### **Customer Demographics Trends**:
- **Customer Segments**: **Millennials** (ages 25-40) make up the largest group of buyers, accounting for over 50% of sales.
- **Region-Based Trends**: **North America** is the top-performing region, while **Asia** shows potential for future growth.

---
#   Recommendations

 #### **Sales Optimization**:
    1. **Focus on High-Margin Products**: Invest more in high-margin product categories like **electronics**, while controlling costs on low-margin items.
    2. **Promotional Strategies**: Expand promotional events during low sales months (e.g., May-August) to balance out seasonal fluctuations.
    3. **Customer Retention Programs**: Launch targeted **loyalty programs** for high-value customers (those contributing to 60% of revenue).

#### **Inventory Management**:
    1. **Demand Forecasting**: Implement better **demand forecasting** tools to prevent stockouts, especially for high-demand categories like **electronics**.
    2. **Inventory Turnover Optimization**: Slow-moving inventory items should be discounted or bundled with popular items to improve turnover.
    3. **Diversify Suppliers**: Explore **multiple suppliers** for high-demand electronics to avoid stockouts during peak sales periods.

#### **Geographic Expansion**:
    1. **Focus on Asia-Pacific**: Invest in **regional marketing** campaigns to tap into the growing demand in **Asia-Pacific**, especially in emerging markets.
    2. **Target Millennials**: Leverage **social media platforms** and influencer marketing to target **Millennials** and increase customer engagement.

---

#   Conclusion

- **Power BI** allowed for deep insights into **Tawilind Traders’ sales, inventory, and profit trends**. 
- **Key drivers** of success include focusing on high-margin products, optimizing inventory management, and leveraging customer demographics to drive sales.
- Recommendations suggest streamlining **inventory management**, enhancing **sales promotions**, and expanding into growing markets like **Asia**.
- By implementing these recommendations, Tawilind Traders can improve its operational efficiency, better meet customer demand, and sustain growth in the long run.


