Netflix Content Analysis

 Project Overview
This project analyzes Netflix’s content catalog using Excel, SQL, and Power BI to uncover trends in content type, audience focus, country-wise production, and release behavior.

The goal is to simulate a real-world data analyst workflow: 
data cleaning → SQL analysis → interactive dashboard.

Tools Used
- Excel (Data cleaning & feature creation)
- MySQL (Business analysis using SQL)
- Power BI (Dashboard & visualization)

Key Business Insights
- 96% of Netflix titles in this dataset are Movies, showing a strong platform focus on movie-based content.
- The United States contributes about 40% of Netflix’s total content, followed by India as the second largest producer.
- Over 50% of Netflix content is rated TV-MA or R, indicating Netflix targets mature audiences.
- Netflix adds most of its content on Wednesdays, Thursdays, and Fridays, aligning releases with peak viewer engagement.


Dataset
The cleaned Netflix dataset contains the following fields:
- show_id
- type
- title
- director
- cast
- country
- date_added
- Weekday
- year_added
- release_year
- rating
- duration


 Files in this Repository
| Folder | Description |
| data | Cleaned Netflix dataset (CSV) |
| sql | SQL script used to create tables and insert data |
| powerbi | Power BI dashboard file |
| README.md | Project documentation |

 Dashboard
 
The Power BI dashboard includes:
- Total Titles, Movies, and TV Shows KPI cards
- Movies vs TV Shows comparison
- Top producing countries
- Content rating distribution
- Day-wise content release trends


