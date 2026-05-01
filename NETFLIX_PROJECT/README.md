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

# Key BUSINESS QUESTIONS

    1. Which genres are most popular globally and by country?
    2. Do TV shows or Movies attract more content volume over the years?
    3. Which countries produce the most content?
    4. What genres dominate in high-content countries?
    5. Is there a trend of increasing content production over years?

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

# Workflow of this project:
Here's a comprehensive outline for a **Netflix Data Analytics Power BI Project** including:

        - Exploratory Data Analysis (EDA)
        - Insights and Findings
        - Trends
        - Recommendations
        - Conclusion

# Netflix Data Analytics Project Using Power BI (Methodology)

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


# Data Cleaning
In the initial data preparation phase, I performed the following tasks:

    •	Data loading and inspection
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

            •	Changing data types
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

# Dashboard Design and Creation

    With the processed data, I created a Netflix data analytics dashboard that presents key insights on content. The dashboard includes charts showing trends of content, count of TV shows and Movie,Around the world  providing a comprehensive view of factors contributing to attrition within the company. These visualizations can help inform HR decision-making and guide targeted efforts to reduce attrition and retain valuable employees.

![alt text](<Images/NETFLIX DATA VISUALITION REPORT.png>)

# Insights

    Creating a **Netflix Data Analytics Power BI project** can provide insightful findings into user behavior, content performance, genre trends, and more. Here’s a summary of what such a project can include and the **key findings** you might highlight.

# Key Findings

    1. Genres: Comedy, Drama, and Documentaries dominate; over 60% of content is concentrated in a few genres
    2. Movies make up ~80% of the catalog; TV shows ~20%.
    3. Major growth in content additions occurred between 2017–2019.
    4. The U.S., India, and the UK lead in content production/availability.
    5. Most movies are 80–120 minutes; very few exceed 2.5 hours.


# Recommandation

    1. Invest more in underrepresented genres (e.g., sci-fi, thriller, animation) to reduce over-reliance on a few categories.
    2. Expand series content to boost engagement and retention (binge-watching behavior).
    3. Continue investing in high-performing markets (India, UK) while expanding into emerging regions.
    4. Maintain the 80–120 minute range, as it aligns with viewer preferences.
    5. Replicate the 2017–2019 strategy by periodically increasing original, high-quality releases to drive growth.


