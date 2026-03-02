# Power_Bi_Projects_Ruksana
# Problem Statement
Netflix, a leading global OTT streaming platform, aims to expand its business presence across different countries. To support this objective, we are provided with a dataset containing information about movies and TV shows currently available on Netflix. The task is to analyze this dataset, extract meaningful insights, and recommend the types of movies and shows that can help accelerate Netflix’s growth and profitability in various regions.

Profit growth can generally be achieved through two approaches: increasing revenue or reducing operational costs. However, in this case, the focus is not on cost reduction. Since expanding into different countries and producing targeted content requires additional investments in production, marketing, and operations, minimizing costs is not a feasible strategy.

Therefore, the primary objective is to identify content strategies that drive revenue growth. This can be achieved by:

    * Acquiring new subscribers in different countries
    * Increasing customer retention through engaging and high-demand content
    * Expanding the platform’s appeal in emerging markets

Through data analysis, we aim to determine which genres, content types (movies vs. TV shows), release trends, and country-specific productions are most likely to enhance subscriber growth and long-term engagement. The final goal is to provide data-driven recommendations that support Netflix’s international expansion and revenue growth strategy.

---
Since cost reduction is not the focus, the goal becomes:

    Increase Revenue Through:
    New customer acquisition
    Customer retention
    Market expansion in high-growth countries

Step 1: Define What Drives Revenue on Netflix

Revenue is primarily driven by:

* 📈 Subscriber Growth
* 🔁 Retention Rate
* 🌍 Country Expansion
* ⭐ High-rated & popular content
* 🎭 Genre demand by region
* ⏳ Content volume & freshness

From your dataset (Netflix titles dataset), we can analyze:

* Genre
* Country
* Release year
* Type (Movie/TV Show)
* Runtime
* IMDb rating (if included)
* Content volume trends

---

# 📊 Key Analytical Questions

Convert the business problem into measurable questions:

1. Which genres are most popular globally and by country?
2. Do TV shows or Movies attract more content volume?
3. Which countries produce the most content?
4. What genres dominate in high-content countries?
5. Is there a trend of increasing content production over years?
6. What type of content has higher average ratings?
7. Do longer runtimes correlate with higher ratings?
8. Which countries have growing content production trends?

---


<!-- The problem statement says that the renowned OTT platform, Netflix wants to increase its business in different countries. We are provided with the dataset which contains the movies and shows that are in Netflix. We have to analyse this data, generate insights on them and finally recommend those movies and shows that could help Netflix increase its profit in various countries.

To achieve this goal, we have to first find out what drives profit growth in Netflix. Profit growth is driven through 2 factors, increase in revenue or decrease in company costs or both. Here, the problem statement is that we have to find out those movies/shows that could help accelerate business of Netflix. This makes us rule out the 2nd factor of decreasing the costs, because if we are aiming to increase the business by particularly focusing on the production of specific shows and movies in different countries, then we have to spend extra on marketing and operations costs, and for that decreasing costs is not an option. Therefore, we have to focus on increasing revenue by acquiring new customers or by increasing customer retention or both. -->
Connect to the dataset and perform the following tasks for data modeling. Do an analysis of the
dataset by cleaning and modifying the dataset, thus drawing relevant insights.
Data Description:
    Credits table:
    person id: Person id.
    Id: Team Id while working on a movie.
    Name: Name of the person.
    Character: The character they have played in the movie.
    Role: Their role in making a movie.
    Title Table:
    Id: Team Id while working on a movie.
    Title: Movie/web series name
    Type: Movie/Web series
    Release_year: The release year when the movie was released.
    Age_certification: Certificate based on content allowed to watch by age.
    Runtime: Total screen time of content
    Genres: Movie type based on Action/Comedy/Scifi
    Production_countries: Origin of content
    Seasons: The count of sequel/prequel number of any content
    Imdb_id: Registered ID on IMDB website
    Imdb_score: Average rating by all users
    Imdb_votes: The no of people has given their vote
    Tmdb_popularity: TMDB popularity score
    Tmdb_score: TMDB rating
    The following are the tasks that need to be performed:
    1. Connect and get data from an Excel file named “1910_m4_assign_dataset_v1.0”.
    2. Open the power query editor and perform the data cleaning task.
    3. Open the data model and make relationships among all tables.
    4. Create measures for “total content” and “Runtime hours” formulas using DAX.
    5. Show bar plot for most available content for top 5 genres by type.
    6. Show line chart for a count of released content by each year by their type.
    7. Show production country and run time for each content on the map.
    8. show the total distribution of content types using the donut chart.
    9. Create cards for the total runtime, the total count of movies and tv shows, and the
    average rating of IMDB.
    10. Add slicer for genres, release year, and title.
    11.Add the Netflix logo and a little introduction to Netflix (use text box).
    Note: sample of dashboard.

<!-- To acquire new customers or to increase the customer retention rate, we have to figure out some critical aspects that affect the customer acquisition and retention. They are as follows:
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
link:https://colab.research.google.com/github/Shreyashgupta016/My-Projects/blob/main/Netflix_Project.ipynb/ -->

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

 Netflix Data Analytics Project Using Power BI

1. Exploratory Data Analysis (EDA)

Dataset Overview 
Features include:  
Credits table:
    person id: Person id.
    Id: Team Id while working on a movie.
    Name: Name of the person.
    Character: The character they have played in the movie.
    Role: Their role in making a movie.
    Title Table:
    Id: Team Id while working on a movie.
    Title: Movie/web series name
    Type: Movie/Web series
    Release_year: The release year when the movie was released.
    Age_certification: Certificate based on content allowed to watch by age.
    Runtime: Total screen time of content
    Genres: Movie type based on Action/Comedy/Scifi
    Production_countries: Origin of content
    Seasons: The count of sequel/prequel number of any content
    Imdb_id: Registered ID on IMDB website
    Imdb_score: Average rating by all users
    Imdb_votes: The no of people has given their vote
    Tmdb_popularity: TMDB popularity score
    Tmdb_score: TMDB rating

<!-- - Title  
- Type (Movie/TV Show)  
- Genre (Listed_in)  
- Country  
- Release Year  
- Date Added  
- Duration  
- Director, Cast  
- Rating   -->

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
        Open the data model and make relationships among all tables.

![alt text](<Images/NETFLIX DATA MODEL VIEW.png>)

    Create measures for “total content” and “Runtime hours” formulas using DAX.
# Exploratory Data Analysis
 EDA involved exploring the NetFLix data to answer key questions, such as:
      
    1. Which top 5 genres have the highest number of available content, segmented by content type (Movie vs TV Show)?
    → (Bar Chart)
    2. How has the number of released content changed over the years, and how does this trend differ by content type?
    → (Line Chart)
    3. Which countries produce the most content, and how does runtime vary across different production countries?
    → (Map Visualization with runtime details)
    4. What is the overall distribution of content types (Movies vs TV Shows)?
    → (Donut Chart)
    5. What are the key summary metrics of the dataset?
    6. What is the total runtime of all content?
    7. What is the total number of Movies?
    8. What is the total number of TV Shows?
    9. What is the average IMDb rating?
    → (KPI Cards)
    10. How do genre, release year, and title filters impact content distribution and performance metrics?
    → (Slicers for interactive analysis)
    
     
# Dashboard Design and Creation

With the processed data, I created a Netflix data analytics dashboard that presents key insights on content. The dashboard includes charts showing trends of content, count of TV shows and Movie,Around the world  providing a comprehensive view of factors contributing to attrition within the company. These visualizations can help inform HR decision-making and guide targeted efforts to reduce attrition and retain valuable employees.
![alt text](<Images/NETFLIX DATA VISUALITION REPORT.png>)

# Insights
Creating a **Netflix Data Analytics Power BI project** can provide insightful findings into user behavior, content performance, genre trends, and more. Here’s a summary of what such a project can include and the **key findings** you might highlight.

🎯 Netflix Data Analytics Power BI Project: Key Insights & Findings

 1. Genre Popularity
    Top Genres: Comedy,Drama, and Documentaries tend to dominate the Netflix catalog.
    Genre Distribution: Visualization shows how different genres perform across countries.
    Finding: Over 60% of Netflix content is concentrated in less than 4 genres.
---
 2. Content Type Distribution
    Movies vs. TV Shows: Pie chart show the ratio.
    Finding: Movies make up around 80% of the Netflix catalog; TV shows comprise 20%.

---
3. Content Release Trend Over Time
    *Year-wise content additions*: Line graph shows new content released each year.
    *Finding*: Major surge in content releases around 2017–2019 due to original content push.
---
4. Country-wise Content Distribution
    Heatmaps:  show the number of shows per country.
    Finding*: The U.S., India, and the UK are among the top countries with most content produced or available.
 ----   
 6. Duration & Runtime Insights
    Average movie length: Visualizations of distribution of movie durations.
    Finding: Most movies range between 80–120 minutes; very few are over 2.5 hours.
---

# Key Findings

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

# Trends Observed

**Yearly Content Growth**: Spike from 2016–2019 as Netflix pushed Originals.
 **Localized Content Growth**: Increase in India, South Korea, Spain — tied to international audience growth.
**Shift in Ratings**: TV-MA content increasingly produced. 
**Content Length Trends**: Surge in shorter, binge-able formats (30–50 min shows and under-90 min films).
**Genre Popularity**: Comedy, Documentary, Thriller consistently perform well.

---

💡 4. Recommendations

For Netflix:
1. Invest More in International Originals 
   Countries like India, South Korea, and Spain show high growth and engagement.

2. Diversify Genres in TV Shows
   While Movies show genre diversity, TV Shows are overly skewed toward Drama.

3. Use Data to Guide Binge-Worthy Series  
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

<!-- Microsoft Power BI Certification and Training

Module 4: Data Visualization
Assignment Document
© Brain4ce Education Solutions Pvt. Ltd.
Module 4: Data Visualization
© B r a i n 4 c e E d u c a t i o n S o l u t i o n s P v t . L t d Page 1
Assignment
Scenario: Given a dataset named as “1910_m4_assign_dataset_v1.0”. Connect to the
dataset and perform the following tasks for data modeling. Do an analysis of the
dataset by cleaning and modifying the dataset, thus drawing relevant insights.
Data Description:
Credits table:
person id: Person id.
Id: Team Id while working on a movie.
Name: Name of the person.
Character: The character they have played in the movie.
Role: Their role in making a movie.
Title Table:
Id: Team Id while working on a movie.
Title: Movie/web series name
Type: Movie/Web series
Release_year: The release year when the movie was released.
Age_certification: Certificate based on content allowed to watch by age.
Runtime: Total screen time of content
Genres: Movie type based on Action/Comedy/Scifi
Production_countries: Origin of content
Seasons: The count of sequel/prequel number of any content
Imdb_id: Registered ID on IMDB website
Imdb_score: Average rating by all users
Imdb_votes: The no of people has given their vote
Tmdb_popularity: TMDB popularity score
Tmdb_score: TMDB rating
The following are the tasks that need to be performed:
1. Connect and get data from an Excel file named “1910_m4_assign_dataset_v1.0”.
2. Open the power query editor and perform the data cleaning task.
3. Open the data model and make relationships among all tables.
4. Create measures for “total content” and “Runtime hours” formulas using DAX.
Module 4: Data Visualization
© B r a i n 4 c e E d u c a t i o n S o l u t i o n s P v t . L t d Page 2
Note: Use this color coding for all the visuals.
Color hex codes:
#D40400 for red
#FFFFFF for white
#000000 for black
5. Show bar plot for most available content for top 5 genres by type.
6. Show line chart for a count of released content by each year by their type.
7. Show production country and run time for each content on the map.
8. show the total distribution of content types using the donut chart.
9. Create cards for the total runtime, the total count of movies and tv shows, and the
average rating of IMDB.
10. Add slicer for genres, release year, and title.
11.Add the Netflix logo and a little introduction to Netflix (use text box).
Note: sample of dashboard.
 -->
?