Introduction
Objective of the Project
This report analyzes the performance of movies and TV shows based on various attributes such as IMDb scores, popularity, production countries, genres, and season counts using data from TMDB (The Movie Database) and IMDb (Internet Movie Database).
Problem Being Addressed
Entertainment platforms often struggle to optimize content recommendations, make licensing decisions, and invest in specific genres or formats without detailed data insights. This dashboard provides a consolidated view of performance indicators that can help optimize content.
Key Datasets and Methodologies
The analysis utilizes datasets that include:
•	Runtime
•	Genres
•	IMDb scores
•	TMDB popularity
•	Vote counts
•	Release year
•	Production countries
The methodology involves aggregation, grouping, and visualization using business intelligence tools like Power BI or Tableau for comparative and trend analysis.
Story of Data
Data Source
The primary sources for this analysis are:
•	TMDB (The Movie Database)
•	IMDb (Internet Movie Database)
Data Collection Process
Data was gathered through APIs or data exports from TMDB and IMDb, collecting metadata for movies, including titles, release years, scores, votes, and popularity metrics.
Data Structure
Each entry in the dataset contains:
•	Title
•	Release Year
•	IMDb ID
•	Runtime
•	Genres
•	Production Countries
•	IMDb Score
•	TMDB Popularity
•	Vote Count
•	Description
•	Number of Seasons (for TV shows)
Important Features and Their Significance
•	IMDb Score: Indicates audience reception.
•	TMDB Popularity: Reflects online engagement.
•	Genres: Useful for understanding content preferences.
•	Production Countries: Influences language, culture, and budget.
•	Season Count: Indicates longevity and viewer retention.
Data Limitations or Biases
•	Genre data may be overly nested or repetitive.
•	Popularity scores can be influenced by recent trends or viral content.
•	Some data fields may contain non-English text, which could hinder standardized analysis.
Data Splitting and Preprocessing
Data Cleaning
•	Inconsistent or duplicate genre arrays were cleaned.
•	Production country codes were normalized (e.g., ‘US’, ‘JP’).
•	Entries with incomplete IMDb IDs were removed or tagged.
Handling Missing Values
Missing TMDB popularity and IMDb scores were either excluded or filled in using mean scores from similar genres or titles.
Data Transformations
•	Aggregated values for votes, popularity, and scores.
•	Unpacked nested genre arrays.
•	Calculated counts (e.g., seasons per title).
Data Splitting
Data was divided by title, genres, production countries, and type (e.g., TV show or movie).
Industry Context
This analysis is relevant for streaming services, studios, content marketers, and media analysts.
Stakeholders
•	Streaming Platforms (e.g., Netflix, Prime Video)
•	Production Studios
•	Marketing Teams
•	Content Acquisition Departments
Value to the Industry
The insights provided allow stakeholders to identify high-performing content, optimize genre investments, and evaluate regional production value.
Pre-Analysis
Identify Key Trends
•	Shows like NCIS and Pokémon have the most seasons.
•	The United States leads in content popularity.
•	Certain genres, such as Drama and Western, show strong IMDb scores.
Potential Correlations
•	A higher number of seasons often aligns with strong viewer engagement.
•	Popularity is more concentrated in U.S.-produced content.
•	Certain genres correlate with higher average IMDb scores.
Initial Insights
•	IMDb scores don’t always align with TMDB popularity.
•	Content from Japan and Korea, while less in quantity, has niche high popularity.
In-Analysis
Unconfirmed Insights
•	Some titles have high popularity but lower IMDb scores, suggesting that viral content may not always receive critical acclaim.
•	Non-English content may be underrepresented in high IMDb scores, possibly due to audience bias or scoring language limitations.
Recommendations
•	Invest more in genres with consistently high IMDb scores (e.g., Drama, Western).
•	Increase acquisition of high-popularity international content for niche markets.
•	Use TMDB popularity as a leading indicator for marketing focus.
Analysis Techniques Used
•	Descriptive analytics
•	Aggregated statistics (sum, mean)
•	Ranking and top-N analysis
•	Comparative bar and pie chart visualizations
Post-Analysis and Insights
Key Findings
•	Western drama genres consistently score high on IMDb.
•	U.S.-produced titles dominate TMDB popularity.
•	Titles like Zumbo's Just Desserts and ZZ Top show exceptional popularity.
•	Titles with high season counts demonstrate stronger longevity.
Comparison with Initial Findings
The analysis confirmed that production country and genre type influence popularity and ratings. However, high TMDB popularity does not always reflect critical acclaim.
Data Visualizations & Charts
Charts and Graphs
•	Pie Chart: TMDB popularity by type
•	Bar Charts: IMDb scores by genres and seasons by title
•	Tree Map: Popularity by title
•	Column Chart: Popularity by production country
Dashboards
An interactive dashboard allows users to filter by title, genre, and production country.
Explanation of Visualizations
Each graph provides insights from different perspectives:
•	Pie/Tree Maps: Show the proportional distribution of popularity.
•	Bar Charts: Offer comparative analysis of seasons, scores, and countries.
•	Runtime vs. Genre Gauge: Indicates total content runtime.
Recommendations and Observations
Actionable Insights
•	Expand content in top genres (e.g., Western, Drama).
•	Localize and promote foreign content with growing TMDB popularity.
•	Track popularity over time to predict future hits.
Optimizations or Business Decisions
•	Adjust licensing budgets based on genre and country of origin.
•	Enhance recommendation algorithms to consider both IMDb scores and TMDB popularity.
Unexpected Outcomes
Some lower IMDb-rated content had significantly high popularity, highlighting the importance of audience engagement over critical reviews.
Conclusion
Key Learnings
•	There is a nuanced balance between critical acclaim and viewer popularity.
•	U.S. content dominates, but global niches exist.
•	Genres and seasons are strong indicators of success longevity.
Limitations
•	Language inconsistencies in title names.
•	Lack of time-series trends (e.g., year-over-year growth).
•	Potential bias in IMDb ratings based on viewer demographics.
