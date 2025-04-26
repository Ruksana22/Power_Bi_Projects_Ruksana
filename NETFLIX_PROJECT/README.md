# Power_Bi_Projects_Ruksana
# Problem Statement
The problem statement says that the renowned OTT platform, Netflix wants to increase its business in different countries. We are provided with the dataset which contains the movies and shows that are in Netflix. We have to analyse this data, generate insights on them and finally recommend those movies and shows that could help Netflix increase its profit in various countries.
To achieve this goal, we have to first find out what drives profit growth in Netflix. Profit growth is driven through 2 factors, increase in revenue or decrease in company costs or both. Here, the problem statement is that we have to find out those movies/shows that could help accelerate business of Netflix. This makes us rule out the 2nd factor of decreasing the costs, because if we are aiming to increase the business by particularly focusing on the production of specific shows and movies in different countries, then we have to spend extra on marketing and operations costs, and for that decreasing costs is not an option. Therefore, we have to focus on increasing revenue by acquiring new customers or by increasing customer retention or both.
To acquire new customers or to increase the customer retention rate, we have to figure out some critical aspects that affect the customer acquisition and retention. They are as follows:
	•	What type/genre of movies are generally seen and rated higher in various countries? What is the watch time of these movies?
	•	Which actors/actresses’ or director’s movies are preferred in various countries and globally?
	•	Is the global trend shifting towards series from movies? If yes, then what all countries are the forerunner in it?
	•	What type of movies/shows are watched by what age-group of people (demographics)? Also, what is the time each age-group of people spend on Netflix?
	•	How has the number of movies released per year changed over the years?

	•	Does seasonality affects the users on Netflix? If yes, then in which season/month Netflix record the largest number of subscriptions?
	•	What all shows are binge-watched on Netflix?
	•	Is there a possibility to enter new market/country?
	•	Does discount on festivals increase the user inflow?
	•	What are the evergreen shows i.e. shows that became superhit in the past?
We will try to find the answers of most of these questions (as per the limitations of the data) through our exploratory data analysis, and will build our insights accordingly.
link:https://colab.research.google.com/github/Shreyashgupta016/My-Projects/blob/main/Netflix_Project.ipynb/

# Tools
Tools used for Data Cleaning, Data Analysis and Report generation:

    •	Excel
    •	PowerBI
    •	PowerBI Service


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

    EDA involved exploring the HR data to answer key questions, such as:
    •	What are the recruitment trends?
    •	What are New Hires, Retention and Separation trends?
    •	What are Male, and Female staff with age groups that have been retained over the years in every region?

# Dashboard Design and Creation

With the processed data, I created a HR analytics dashboard that presents key insights on employee attrition. The dashboard includes charts showing attrition rates by department, age, salary, and job satisfaction, providing a comprehensive view of factors contributing to attrition within the company. These visualizations can help inform HR decision-making and guide targeted efforts to reduce attrition and retain valuable employees.
![alt text](<Images/NETFLIX DATA VISUALITION REPORT.png>)


# Things done in this project:

    •	Loading and Cleaning Data: Import data into Power BI and use Power Query to clean and prepare it.
    •	Creating HR Metrics: Calculate essential HR metrics such as headcount, average leave balance, and average salary using Power Pivot.
    •	Data Enrichment: Add meaningful columns to the data, such as Employee's first name and age group.
    •	Salary Analysis: Explore relationships between salary and educational qualifications.
    •	Visual Filters: Apply filters to view top and bottom paid staff within each job role.
    •	Customizing Visuals: Modify visual elements in Power BI, including colors, axes, labels, and legends.
    •	Advanced DAX Calculations: Perform advanced calculations like cumulative headcount and leave balances exceeding 20 days.
    •	Dashboard Design: Create a detailed monthly HR dashboard with Power BI.
    •	Using Card Visuals: Work with the "NEW" card visual to highlight specific metrics.
    •	The project addresses the following analysis themes:
    •	Job Count Analysis: Determine how many people are employed in each job role.
    •	Gender Breakdown: Analyze the gender distribution among the staff.
    •	Age Distribution: Examine the age spread of the employees.
    •	Salary Analysis: Identify which job roles have higher salaries.
    •	Top Earners: Find the top earners within each job role.
    •	Qualification vs. Salary: Explore the correlation between educational qualifications and salary.
    •	Staff Growth Trend: Analyze the trend of staff growth over time.
    •	Employee Filter: Filter employees based on the starting letter of their name.
    •	Leave Balance Analysis: Review leave balances, especially focusing on those exceeding 20 days.
    •	HR Dashboard: Design a HR dashboard to consolidate and visualize key metrics.

# Insights

# 1. Employee Statistics
    Total Number of Employees Over Time:
    •	2017: 1 employee
    •	2023: 161 employees
    •	Growth: Significant increase in the number of employees from 1 in 2017 to 161 in 2023.
    Gender Distribution:
    •	Total Male Employees: 73
    •	Total Female Employees: 88
    •	Total Employees: 161
    •	Gender Ratio: More females than males in the workforce.
# 2. Employee Roles and Distribution:
    Highest Number of Employees by Role:
    •	Packaging Associate: 22 employees Note: This role has the more number of employees compared to others.
    Lowest Number of Employees by Role:
    •	Marketing Manager: 10 employees
    •	Marketing Specialist: 10 employees Note: These roles have the less number of employees.
# 3. Age Distribution:
    Female Employees Aged 30:
    •	Number of Employees: 44
    •	Significance: This is the highest number of female employees in a single age group.
    Male Employees Aged 30:
    •	Number of Employees: 41
    •	Significance: This is the highest number of male employees in a single age group.
# 4. Salary Information:
    Overall Salary Metrics:
    •	Average Salary: $54,231
    •	Minimum Salary: $28,900
    •	Maximum Salary: $85,000
    Role-Specific Salary Details:
    •	Highest Average Salary: Product Manager - $82,825
    •	Lowest Average Salary: Packaging Associate - $33,409
    •	Highest Maximum Salary: Product Manager - $85,000
    •	Lowest Minimum Salary: Packaging Associate - $28,900
    Educational Qualification and Salary:
    •	Highest Salary (Masters Degree): $85,000
    •	Lowest Maximum Salary (Bachelor's Degree): $78,900
# 5. Leave Balance Information:
    •	Average Leave Balance: 16.4 days
    •	Number of Employees with Leave Balance Greater Than 20 Days: 29
    •	Significance: Indicates that a portion of the workforce has a significant leave balance.
    Visualizations
    The dashboard includes the following visualizations:
    •	Employee count per job title: Bar Chart
    •	Employee percentage by gender: Pie Chart
    •	Employee count per year: Line Chart
    •	Employee count by age and gender: Coloumn Chart
    •	Maximum Salary Based on Educational Qualification: Scatter Chart
    •	Headcount, Average Salary, Average Leave Balance and Leave Balance more than 20 days: Card

# Insights
The Analysis results are summarized as follows:
    •	The company has over 13k employees, Male staff is around 57% and Female staff is 43%.
    •	Over the past few years, from 2011 till 2014, 11.76K employees have left jobs and noticeably Male staff is higher % as compared to Female staff members.
    •	The New Hires trend is upward every year with 17.18K new hires from 2011 till 2014.
    •	Age group of 30 and less are more compared to 30+ employees. Noticeably, new hires under the age of 30 are working as part-time jobs and in West and North regions.
    •	Employee retention is less in the West and North regions considering these regions have higher recruitment compared to all other regions.

# Recommendations
    Based on the analysis, I recommend the following actions:
    •	The company must focus on West and North regions for employee retention. Management can look into deploying some new measures, programs, perks or benefits for existing employees to ensure they will not leave the company.
    •	Implement a strategy to retain talented employees who will be an asset to a company.
  
# Conclusion
The workforce has grown significantly from 2017 to 2023, reflecting the company’s expansion. There is a higher number of 
Recommendations:

To improve business, it is required that the Netflix should focus on the top 10 countries which produces 77% of the total movies and tv shows as per the audience preferences. This is the area from where the maximum business can flow in.
The Netflix should add more movies and tv shows that employ the actors/actresses who have worked the most, as these celebrities have a huge fan base in those specific countries and will attract larger audience, especially US where actors like Samuel L. Jackson, Tara Strong, Adam Sandler not only attracts home crowd but the foreign crowd as well due to the commonality of English language in many countries. Similarly Anupam Kher who has been a seasoned actor and Shahrukh Khan who rules Bollywood industry. Apart from that, it is recommended to add more movies and tv shows of particular genres that are being produced the most in individual countries such as the tag of International Movies in India, for example ‘My Name is Khan’, which is a Shahrukh Khan movie was a blockbuster hit.
The focus has been rapidly shifting from movies to the tv shows in the recent years, which is also supported by our analysis, as we saw almost 1270% increase in the production of new tv shows after 2010. These shows need not be very long but short, primarily of 1 season or such. TV Shows today are creating a sense of connectivity more than the movies and as a result people are focusing on these shows more. At the same time, it is also recommended that we add International TV Shows more because of their rapid rise in the past 20 years.
We should offer some discounts during the festival season especially during the New Year’s time as we can see from the data that most of the addition of movies are done during this time of the year. The discounts or subsidies will greatly increase the user flow and will add more people during the festivals’ time especially in the second half of the year. Also, ratings matter a lot in movies business. Therefore, it is recommended to prioritize adding those movies/tv shows which are mostly suited to individuals above 14 years of age, as the highest rating for most of the movies/tv shows are TV-MA.


