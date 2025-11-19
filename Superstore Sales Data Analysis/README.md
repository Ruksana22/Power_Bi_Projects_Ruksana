# Problem Statement
The problem statement s

# Tools
Tools used for Data Cleaning, Data Analysis and Report generation:

    •   Excel
    •	PowerBI
        🔧 Tools & Visuals Used in Power BI:
        - Slicers for year, genre, type
        - Line and bar charts for trends
        - Treemaps for categorical data (genres, countries)
        - Custom tooltips for details on hover
        - KPI cards for summary statistics (total movies, total shows, top genre)

Here's a comprehensive outline for a ** Superstore Sales Data Analytics Power BI Project** including:

- Exploratory Data Analysis (EDA)
- Insights and Findings
- Trends
- Recommendations
- Conclusion

---

## 📊 **Superstore Sales Data Analytics Project Using Power BI**

---
1. Exploratory Data Analysis (EDA)**

**Dataset Overview**:  
Features include:  
- Title  
- Type (Movie/TV Show)  
- Genre (Listed_in)  
- Country  
- Release Year  
- Date Added  
- Duration  
- Director, Cast  
- Rating  

EDA in Power BI includes:  
- Null/missing data checks (e.g., missing directors or cast data)
- Data types formatting (duration into numeric values)
- Date conversion for trends over time
- Filters for country, type, genre

Initial Cleaning Tasks:
- Split and normalize `Genre` and `Country` fields
- Create new fields: `Year Added`, `Duration in minutes`, `Content Age Group`
- Remove duplicates and null-heavy records

---

# Data Cleaning
In the initial data preparation phase, I performed the following tasks:

    •	Data loading and inspection,
    •	Changing data types,
    •	Optimizing the dataset by removing unnecessary and duplicate columns,
    •	Standardizing abbreviations used in the dataset,
    •	Handling missing values,
    •	Data cleaning and formatting

# Data Modeling

    •	Managing Relationships between different tables.
![alt text](<Images/NETFLIX DATA MODEL VIEW.png>)


# Exploratory Data Analysis
 EDA involved exploring the NetFLix data to answer key questions, such as:
    •	What are the NetFlix content trends?
    •	What are count genere and Separation trends?
    
# Dashboard Design and Creation

With the processed data, I created a Netflix data analytics dashboard that presents key insights on content. The dashboard includes charts showing trends of content, count of TV shows and Movie,Around the world  providing a comprehensive view of factors contributing to attrition within the company. These visualizations can help inform HR decision-making and guide targeted efforts to reduce attrition and retain valuable employees.
![alt text](<Images/NETFLIX DATA VISUALITION REPORT.png>)

# Insights
Creating a **Superstore Sales Data Analytics Power BI project** can provide insightful findings into user behavior, content performance, genre trends, and more. Here’s a summary of what such a project can include and the **key findings** you might highlight.

🎯 Netflix Data Analytics Power BI Project: Key Insights & Findings

 ✅ 1. Genre Popularity
- 🔍 *Top Genres*: Comedy,Drama, and Documentaries tend to dominate the Netflix catalog.
- 📊 *Genre Distribution*: Visualization shows how different genres perform across countries.
- ✅ *Finding*: Over 60% of Netflix content is concentrated in less than 4 genres.

---

# PowerBI-superstore-analysis
This repository contains a Power BI dashboard and report analyzing the Superstore Sales dataset. The project includes data cleaning, visualization, and key business insights to support decision-making.

# 📊 Superstore Sales Analysis – Power BI Assignment

## 📌 Project Overview
This project analyzes the Superstore Sales dataset using **Power BI**, focusing on key business metrics, trends, and actionable insights.

## 📂 Repository Contents
- **Superstore_Sales_Dashboard (.pbix)**: Interactive Power BI dashboard
- **Report - Summarizing Key Insights (.docx)**: Summary of key findings and business recommendations
- **Sales Dashboard (.png)**: Screenshot of the Dashboard

## 📊 Key Insights
- **Total Sales**: $514,292.93 | **Total Profit**: $92,305.79 | **Total Quantity Sold**: 5,491 units
- **Top Product by Profit**: Paper 20 ($618.21) | **Lowest**: Tables 42 ($0.92)
- **Category Performance**: Furniture generates the highest revenue ($177,215.44), but Office Supplies has the best balance between revenue ($169,664.66)
-  and profit ($30,517.34).
- **Regional Performance**: South Region leads with $23,706.49 profit and West Region has the least ($22,686.86).

## ✅ Drillthrough Feature (Scatter Plot):
Implemented a drillthrough on the scatter plot visual that analyzes the impact of discounts on profit margins.
Users can click on sub-categories in the scatter plot to access a detailed product-level breakdown on a dedicated page—offering deeper insights into products performance.

## 📈 Business Recommendations
1. **Optimize Product Strategies**: Focus on high-profit products; review pricing for low-margin items.
2. **Enhance Regional Performance**: Improve marketing in underperforming regions like the West.
3. **Improve Logistics**: Address slow delivery times in Texas and Illinois for better customer satisfaction.

---

<details><summary>Project Report Video shown below:</summary>
<video width="650" height="360" controls autoplay muted loop>
<source src="Files/Images/Dashboard Video.mp4" type="video/mp4">
click the Github Page Link to see the video
</video> </details>
<details><summary>Project Dashboard Sreenshot shown below:</summary>  
<img src="Files/Images/Sales Dashboard Superstore.JPG" width="400" height="250" /> &nbsp;&nbsp; <img src="Files/Images/Dashboard Forecast.JPG" width="400" height="250" /></details>  <br>

<details><summary> <b>Objective</b> :</summary>  To contribute to the success of a business by utilizing techniques, specifically focusing on time series analysis, to provide valuable insights and accurate sales forecasting.<br>
- Dashboard Creation<br>
- Data Analysis<br>
- Sales Forecasting<br>
- Actionable Insights and Recommendations<br>
</details><br>

<details><summary><strong>Business Insights Report: Analyzing Key Findings</strong></summary>
<br>

<b>Executive Summary:</b> <br>
This report presents a comprehensive analysis of key findings derived from our business data. By examining payment modes, regions, customer segments, sales performance, profitability, shipping modes, product categories, sales forecast, and state-wise sales, we have gained valuable insights that can guide our business decisions and strategies. These findings shed light on customer preferences, market dynamics, and areas of opportunity. By leveraging these insights, we can optimize our operations, drive sales growth, and enhance profitability.<br><br>



<b>Regional Analysis:</b><br>
The West region stood out with the highest sum of sales, accounting for 33.37% of the total. This dominance presents an opportunity to allocate additional resources for marketing and promotional activities tailored to this region. By understanding customer preferences and establishing strong local partnerships, we can enhance brand visibility and engage effectively with the West region's market.<br><br>

<b>Segment Analysis:</b><br>
The Consumer segment was the top contributor to sales, accounting for 48.09% of the total sum. To capitalize on this segment's potential, we should implement personalized marketing campaigns, loyalty programs, and customer retention initiatives. Understanding consumer preferences and delivering exceptional customer service will be key to strengthening our position in this segment.<br><br>

<b>Sales Analysis:</b><br>
Sales in 2020 surpassed those in 2019, indicating positive growth. December was a critical month, contributing 10.61% of the total sum of sales in 2020. We should leverage the holiday season by designing targeted marketing campaigns, offering exclusive promotions, and optimizing inventory management. Providing excellent customer service during this peak period will enhance customer satisfaction and drive repeat business.<br><br>

<b>Profit Analysis:</b><br>
Profitability in 2020 outperformed 2019, with December 2019 and March 2020 being notable months. By analyzing these divergences, we can identify the underlying factors and develop strategies to optimize profitability. Factors such as seasonality, market conditions, costs, pricing, and customer behavior should be carefully evaluated to mitigate risks and improve profitability throughout the year.<br><br>

<b>Shipping Mode Analysis:</b><br>
Standard Class emerged as the most preferred shipping mode, accounting for 58.27% of the total sum of sales. Understanding customer preferences for different shipping modes will help optimize logistics and improve customer satisfaction. Balancing efficiency and cost-effectiveness while meeting customer expectations should be a priority across all shipping modes.<br><br>

<b>Product Category Analysis:</b><br>
Office Supplies led in sales, followed by Technology and Furniture. Office Supplies accounted for 41.11% of the total sum of sales, highlighting its popularity. By understanding the demand and preferences for each category, we can optimize product offerings, pricing strategies, and marketing campaigns to maximize sales and profitability.<br><br>

<b>Sales Forecast Analysis:</b><br>
Sales exhibited a significant upward trend, with a 3,924.22% increase between January 1, 2019, and December 31, 2020. Recognizing this trend and understanding the factors driving it, such as promotions or market demand, will allow us to allocate resources effectively and capitalize on future growth opportunities.<br><br>

<b>State-wise Sales Analysis:</b><br>
California dominated sales, with the highest sum, accounting for 30.92% of the total. Analyzing sales performance across states helps us identify potential growth areas, target marketing efforts, and tailor strategies to local market conditions.<br><br>

<b>Conclusion:</b><br>
The findings presented in this report provide valuable insights into various aspects of our business. By analyzing payment modes, regions, customer segments, sales performance, profitability, shipping modes, product categories, sales forecasts, and state-wise sales, we can make informed decisions and formulate strategies to optimize operations, drive growth, and enhance profitability. It is crucial to continue monitoring these metrics, conduct further analysis, and adapt our strategies based on evolving customer preferences and market dynamics. By leveraging these insights effectively, we can stay ahead of the competition and deliver exceptional value to our customers.
</details><br>



<details><summary><strong>Key Learnings from the Power BI Project on Superstore Sales Dashboard:-</strong></summary><br>

1. Data Import: Importing CSV files into Power BI and connecting them to create a dataset for analysis.<br><br>

2. Data Transformation: Using Power Query to clean and prepare the data. This involves removing unnecessary columns and ensuring proper data types for accurate analysis.<br><br>

3. Visual Customization: Changing the canvas background to enhance the overall look and feel of the dashboard.<br><br>

4. Clustered Bar Chart: Creating clustered bar charts to visualize sales by category, subcategory, and ship mode. This allows for easy comparison and identification of trends.<br>
<img src="Files/Images/Filter of Top 3 Sales by Sub Category Bar Chart.JPG" width="350" height="450" /><br><br>

5. Stacked Area Chart: to compare sales and profit year over year. Analyzing monthly sales and profit trends provides insights into performance patterns.<br>
<img src="Files/Images/Area Chart Sales Profit Insight YoY.JPG" width="600" height="350" /><br><br>

6. Map Visualization: Displaying state-wise sales and profit using a map. <br>
- To Enable value on Map follow the steps. File -> Options & Settings -> Options -> Security -> tick 'Use Map and Filled Map Visuals'.  
<img src="Files/Images/Map Value Enable Setting.JPG" width="400" height="400" /><br><br>

7. Donut Chart: to showcase sales by segment, payment mode, and region.<br><br>

8. Slicer: to filer the report by region.<br><br>

9. Display the KPIs using Card.<br> Sum of Sales, Profit, Quantity, Average Delivery Time ( Create New column Step 10)<br><br>

10. Add new Column. This helps analyze the efficiency of order processing and delivery.<br> AvgDeliveryTime = DATEDIFF('SuperStore_Sales_Dataset'[Order Date],'SuperStore_Sales_Dataset'[Ship Date],DAY) <br><br>

11. Sales Forecast: Adding a new page to showcase sales forecast using a line chart visual. This allows users to analyze and predict future sales trends based on historical data.<br><br>

Through these key steps, the Superstore Sales Dashboard in Power BI enables users to gain valuable insights, identify trends, and make data-driven decisions to optimize sales performance and improve overall business outcomes.  
</details>  <br><br>

<details><summary><strong>Credits :</strong></summary>

Thank you Rishabh Mishra for the guidance.<br>

<a href="https://www.youtube.com/watch?v=fZn83JRt4Nk&t=560s">Guided Project Youtube Video Click Here</a>
</details>

<details><summary><strong>See More Projects here:</strong></summary>

1. <a href="https://abhishekmishra8.github.io/Power-BI-Project-Bank-Domain/">Bank Domain Dashboard</a> <br>
2. <a href="https://abhishekmishra8.github.io/PowerBI_Project_HR_Employees/">HR Employees Dashboard</a>

</details>
<br>

[Go To TOP](#TOP)
