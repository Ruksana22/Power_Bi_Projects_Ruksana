# Problem Statement
    Netflix, a leading global OTT streaming platform, aims to expand its business presence across different countries. To support this objective, we are provided with a dataset containing information about movies and TV shows currently available on Netflix. The task is to analyze this dataset, extract meaningful insights, and recommend the types of movies and shows that can help accelerate Netflix’s growth and profitability in various regions.

    Profit growth can generally be achieved through two approaches: increasing revenue or reducing operational costs. However, in this case, the focus is not on cost reduction. Since expanding into different countries and producing targeted content requires additional investments in production, marketing, and operations, minimizing costs is not a feasible strategy.

    Therefore, the primary objective is to identify content strategies that drive revenue growth. This can be achieved by:

        * Acquiring new subscribers in different countries
        * Increasing customer retention through engaging and high-demand content
        * Expanding the platform’s appeal in emerging markets

    Since cost reduction is not the focus, the goal becomes:

        * Increase Revenue Through:
        * New customer acquisition
        * Customer retention
        * Market expansion in high-growth countries   

# Key Analytical Questions

Convert the business problem into measurable questions:

    1. Which genres are most popular globally and by country?
    2. Do TV shows or Movies attract more content volume?
    3. Which countries produce the most content?
    4. What genres dominate in high-content countries?
    5. Is there a trend of increasing content production over years?
    6. What type of content has higher average ratings?
    7. Do longer runtimes correlate with higher ratings?
    8. Which countries have growing content production trends?

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

Workflow of this project:
Here's a comprehensive outline for a **Netflix Data Analytics Power BI Project** including:

        - Exploratory Data Analysis (EDA)
        - Insights and Findings
        - Trends
        - Recommendations
        - Conclusion

Netflix Data Analytics Project Using Power BI
Data Set Column:
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

    Task 1 (Data loading):
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

1. Exploratory Data Analysis (EDA)

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

# Data Cleaning
In the initial data preparation phase, I performed the following tasks:

    •	Data loading and inspection,
    •	Changing data types,
    •	Optimizing the dataset by removing unnecessary and duplicate columns,
    •	Standardizing abbreviations used in the dataset,
    •	Handling missing values,
    •	Data cleaning and formatting
    EDA in Power BI includes:  
        - Null/missing data checks (e.g., missing directors or cast data)
        - Data types formatting (duration into numeric values)
         - Date conversion for trends over time
         - Filters for country, type, genre

Initial Cleaning Tasks:
        - Split and normalize `Genre` and `Country` fields
        - Create new fields: `Year Added`, `Duration in minutes`, `Content Age Group`
        - Remove duplicates and null-heavy records

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

 2. Content Type Distribution
    Movies vs. TV Shows: Pie chart show the ratio.
    Finding: Movies make up around 80% of the Netflix catalog; TV shows comprise 20%.


3. Content Release Trend Over Time
    *Year-wise content additions*: Line graph shows new content released each year.
    *Finding*: Major surge in content releases around 2017–2019 due to original content push.

4. Country-wise Content Distribution
    Heatmaps:  show the number of shows per country.
    Finding*: The U.S., India, and the UK are among the top countries with most content produced or available.
  
 6. Duration & Runtime Insights
    Average movie length: Visualizations of distribution of movie durations.
    Finding: Most movies range between 80–120 minutes; very few are over 2.5 hours.

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


# Trends Observed

Yearly Content Growth: Spike from 2016–2019 as Netflix pushed Originals.
Localized Content Growth: Increase in India, South Korea, Spain — tied to international audience growth.
Content Length Trends: Surge in shorter, binge-able formats (30–50 min shows and under-90 min films).
Genre Popularity: Comedy, Documentary, Thriller consistently perform well.

# Recommendations

For Netflix:
    1. Invest More in International Originals 
   Countries like India, South Korea, and Spain show high growth and engagement.

    2. Diversify Genres in TV Shows
    While Movies show genre diversity, TV Shows are overly skewed toward Drama.
    Expand Drama, Comedy, and Thriller content Focus on TV Series for Retention
    Develop multi-season content Invest in binge-worthy series

    3. Use Data to Guide Binge-Worthy Series Shows with shorter episodes and seasons can boost watch time and retention.

    4. Expand in Emerging Markets  Produce localized content in: India, South Korea, Spain, Brazil

# Conclusion
To improve business, it is required that the Netflix should focus on the top 10 countries which produces 77% of the total movies and tv shows as per the audience preferences. This is the area from where the maximum business can flow in.

- Netflix’s content strategy has leaned heavily into mature, U.S.-centric content, with a rapid increase in original productions between 2016–2020.
- Power BI visualizations clearly highlight opportunities in regional content, family-friendly programming, and genre diversification.
- With international expansion and audience segmentation, Netflix can further personalize offerings and optimize its global content strategy using data.

