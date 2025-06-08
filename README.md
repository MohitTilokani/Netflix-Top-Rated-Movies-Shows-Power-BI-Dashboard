# Netflix-Top-Rated-Movies-Shows-Power-BI-Dashboard

This Power BI project analyzes top-rated Netflix movies and shows based on IMDb data. It provides visual insights using KPIs, charts, maps, and slicers to uncover trends in ratings, genres, votes, and country-based production.

##  Data Source

The dataset consists of multiple interconnected tables including:

Best Movies Netflix
Best Shows Netflix
Best Movie by Year Netflix
Best Show by Year Netflix
Raw Titles
Raw Credits
Table Measures

These tables were related using proper keys and data modeling inside Power BI.

## Data Cleaning

Removed null or blank cells from IMDb scores, titles, and votes
Assigned correct data types (text, number, date)

Created calculated columns and custom DAX measures such as:

Average IMDb Score
Movies to Shows Ratio
Total Duration
Votes per Title
Genre-wise Score Comparison

## Key Features of Dashboard

### ✅ KPIs

##### Total Movies: 387
##### Total Shows: 246
##### Avg IMDb Score (Movies): 7.51
##### Avg IMDb Score (Shows): 8.09
##### Avg Votes Per Movie: 136.5K
##### Avg Votes Per Show: 102.0K
##### Movies to Show Ratio: 1.57

## Visualizations

#### Pie Charts: Year-wise distribution of shows/movies
#### Bar Charts: Top genres by IMDb score
#### Map: Country-wise distribution of titles
#### Slicers/Filters: Year, Continent, Title Type

## Key Insights

Western and Reality Shows have the highest IMDb scores among shows.
Among movies, War, Sci-Fi, and Documentary scored the highest.
The majority of content was released between 2010 and 2019.
The highest volume of content originates from countries like USA, UK, and Japan.
Movies typically have more votes per title compared to shows.

## Tools Used

#### Power BI
#### Power Query Editor (for data transformation)
#### DAX (for custom KPIs and measures)

## Learnings

Built a strong understanding of Power BI data modeling and visual design.
Learned to clean and shape data using Power Query.
Gained experience writing custom DAX measures for business KPIs.
Practiced creating interactive, filterable dashboards that support analysis and decision-making.

 ## Conclusions
 
Netflix offers a wider range of movies compared to shows, both in volume and user votes.
Shows generally have better IMDb ratings than movies, indicating higher content quality or audience retention.
Genres have a strong influence on performance — War and Sci-Fi movies, and Reality/Western shows stand out.
A significant portion of top-rated content was produced between 2010–2019, suggesting that period as a peak in content quality.
The dashboard allows users to easily filter and explore content based on year, genre, and region — providing both strategic and entertainment
