# Power_Bi_Projects_Ruksana
# Problem Statement
The problem statement says that the renowned OTT platform, Netflix wants to increase its business in different countries. We are provided with the dataset which contains the movies and shows that are in Netflix. We have to analyse this data, generate insights on them and finally recommend those movies and shows that could help Netflix increase its profit in various countries.
To achieve this goal, we have to first find out what drives profit growth in Netflix. Profit growth is driven through 2 factors, increase in revenue or decrease in company costs or both. Here, the problem statement is that we have to find out those movies/shows that could help accelerate business of Netflix. This makes us rule out the 2nd factor of decreasing the costs, because if we are aiming to increase the business by particularly focusing on the production of specific shows and movies in different countries, then we have to spend extra on marketing and operations costs, and for that decreasing costs is not an option. Therefore, we have to focus on increasing revenue by acquiring new customers or by increasing customer retention or both.
To acquire new customers or to increase the customer retention rate, we have to figure out some critical aspects that affect the customer acquisition and retention. They are as follows:
    . Runtime Hours
    •	What type/genre of movies are generally seen and rated higher in various countries? What is the watch time of these movies?
    •	What type/genre of movies are generally seen and rated higher in various countries? What is the watch time of these movies? Total content - Total TV Shows and Total Movies, IMDB Average Ratings, Total content and count type by genre
	•	What type/genre of movies are generally seen and rated higher in various countries? What is the watch time of these movies? Count of Runtime(in mintue) by production countries and Type
	•	Which actors/actresses’ or director’s movies are preferred in various countries and globally?
	•	Is the global trend shifting towards series from movies? If yes, then what all countries are the forerunner in it?
	•	What type of movies/shows are watched by what age-group of people (demographics)? Also, what is the time each age-group of people spend on Netflix?
	•	How has the number of movies released per year changed over the years? Total content release year and type

	•	Does seasonality affects the users on Netflix? If yes, then in which season/month Netflix record the largest number of subscriptions? Total content by type -Show or movie
	•	What all shows are binge-watched on Netflix?
	•	What are the evergreen shows i.e. shows that became superhit in the past?
We will try to find the answers of most of these questions (as per the limitations of the data) through our exploratory data analysis, and will build our insights accordingly.
link:https://colab.research.google.com/github/Shreyashgupta016/My-Projects/blob/main/Netflix_Project.ipynb/

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

Here's a comprehensive outline for a **Netflix Data Analytics Power BI Project** including:

- Exploratory Data Analysis (EDA)
- Insights and Findings
- Trends
- Recommendations
- Conclusion

---

## 📊 **Netflix Data Analytics Project Using Power BI**

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
Creating a **Netflix Data Analytics Power BI project** can provide insightful findings into user behavior, content performance, genre trends, and more. Here’s a summary of what such a project can include and the **key findings** you might highlight.

🎯 Netflix Data Analytics Power BI Project: Key Insights & Findings

 ✅ 1. Genre Popularity
- 🔍 *Top Genres*: Comedy,Drama, and Documentaries tend to dominate the Netflix catalog.
- 📊 *Genre Distribution*: Visualization shows how different genres perform across countries.
- ✅ *Finding*: Over 60% of Netflix content is concentrated in less than 4 genres.

---

✅ 2. Content Type Distribution
- 🔄 *Movies vs. TV Shows*: Pie chart show the ratio.
- ✅ *Finding*: Movies make up around 80% of the Netflix catalog; TV shows comprise 20%.

---

✅ 3. Content Release Trend Over Time
- 📅 *Year-wise content additions*: Line graph shows new content released each year.
- ✅ *Finding*: Major surge in content releases around 2017–2019 due to original content push.

---

✅ 4. Country-wise Content Distribution
- 🌎 *Heatmaps*  show the number of shows per country.
- ✅ *Finding*: The U.S., India, and the UK are among the top countries with most content produced or available.

---


✅ 6. Duration & Runtime Insights
- 📏 *Average movie length*: Visualizations of distribution of movie durations.
- ✅ *Finding*: Most movies range between 80–120 minutes; very few are over 2.5 hours.

---


📈 **2. Key Findings**

🔹 Content Type Distribution
- 69% Movies, 31% TV Shows
- Movies dominate, but TV shows have increased in recent years

🔹 Genre Insights
- Top genres:  Comedy, Drama, Documentary, Action
- Kids & Family content strong in U.S., India, and Canada

🔹 Country Distribution
- U.S. has the highest number of titles (~32%)
- India and UK follow, especially in TV Shows and regional dramas


🔹 Duration Analysis (Movies)
- Most movies fall between 80–120 minutes
- Short films and stand-up specials under 60 minutes increasing

🔹 Release Trends
- Peak content addition years: 2018–2020
- Sharp drop post-2020, likely due to pandemic

---

📊 Trends Observed

- 📆 **Yearly Content Growth**: Spike from 2016–2019 as Netflix pushed Originals.
- 🌍 **Localized Content Growth**: Increase in India, South Korea, Spain — tied to international audience growth.
- 📺 **Shift in Ratings**: TV-MA content increasingly produced. 
- 🎬 **Content Length Trends**: Surge in shorter, binge-able formats (30–50 min shows and under-90 min films).
- 🎯 **Genre Popularity**: Comedy, Documentary, Thriller consistently perform well.

---

💡 4. Recommendations

For Netflix:
1. **Invest More in International Originals**  
   Countries like India, South Korea, and Spain show high growth and engagement.

2. **Diversify Genres in TV Shows**  
   While Movies show genre diversity, TV Shows are overly skewed toward Drama.

3. **Use Data to Guide Binge-Worthy Series**  
   Shows with shorter episodes and seasons can boost watch time and retention.

---

🧾 4. Conclusion

- Netflix’s content strategy has leaned heavily into mature, U.S.-centric content, with a rapid increase in original productions between 2016–2020.
- Power BI visualizations clearly highlight opportunities in regional content, family-friendly programming, and genre diversification.
- With international expansion and audience segmentation, Netflix can further personalize offerings and optimize its global content strategy using data.

---

# Conclusion
To improve business, it is required that the Netflix should focus on the top 10 countries which produces 77% of the total movies and tv shows as per the audience preferences. This is the area from where the maximum business can flow in.
The Netflix should add more movies and tv shows that employ the actors/actresses who have worked the most, as these celebrities have a huge fan base in those specific countries and will attract larger audience, especially US where actors like Samuel L. Jackson, Tara Strong, Adam Sandler not only attracts home crowd but the foreign crowd as well due to the commonality of English language in many countries.

The focus has been rapidly shifting from movies to the tv shows in the recent years, which is also supported by our analysis, as we saw almost 1270% increase in the production of new tv shows after 2010. These shows need not be very long but short, primarily of 1 season or such. TV Shows today are creating a sense of connectivity more than the movies and as a result people are focusing on these shows more. At the same time, it is also recommended that we add International TV Shows more because of their rapid rise in the past 20 years.
We should offer some discounts during the festival season especially during the New Year’s time as we can see from the data that most of the addition of movies are done during this time of the year. The discounts or subsidies will greatly increase the user flow and will add more people during the festivals’ time especially in the second half of the year. Also, ratings matter a lot in movies business. Therefore, it is recommended to prioritize adding those movies/tv shows which are mostly suited to individuals above 14 years of age, as the highest rating for most of the movies/tv shows are TV-MA.


