Netflix Content Analysis Dashboard
Project Overview

Developed an interactive Power BI dashboard to analyze Netflix's global content library. The dashboard provides insights into content distribution, ratings, genres, release trends, and country-wise content production.

Key Insights
Total Titles: 8,799
Total Genres: 514
Total Locations: 749
Movies account for approximately 70% of total content.
TV-MA is the most common rating category.
The United States contributes the highest number of titles.
Significant growth in Netflix content production after 2010.
Dashboard Features
Genre Analysis
Rating Distribution
Movies vs TV Shows Comparison
Release Year Trend Analysis
Country-wise Content Distribution
Interactive Filters and Drill-downs
Tools Used
Power BI
Power Query
DAX
Excel/CSV Dataset
Dashboard Preview

Tasks Performed:

Data Cleaning Performed
DAX Measures Created
KPIs Designed
Business Questions Answered

For example:

DAX Measures

Total Titles = COUNTROWS(netflix)

Movies Count =
CALCULATE(
    COUNTROWS(netflix),
    netflix[type]="Movie"
)


Built an interactive Power BI dashboard analyzing 8,799 Netflix titles across genres, ratings, release years, and countries.
Developed KPIs, DAX measures, and visualizations to uncover content trends and geographic distribution.
Improved data exploration through interactive filtering and drill-down capabilities.
