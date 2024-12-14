# Weather Data Analysis and Web Scraping Project (Team 25)

## Project Description
In this project, we, as Team 25, collected and analyzed historical weather data for Baku city. The data was obtained from the historical hourly weather forecast for the following dates:
- October 1st
- November 1st
- December 1st

The data was scraped from the webpages of [timeanddate.com](https://www.timeanddate.com/).

## Team Allocation Table
| Team Member               | Role         | Contribution (%) |
|---------------------------|--------------|------------------|
| Elnama Mammadova          | Team Leader  | 25%              |
| Ravan Mehraliyev          | Member       | 25%              |
| Aykhan Khasiyev           | Member       | 25%              |
| Shamkhal Khalfayev        | Member       | 25%              |

## Github Repository
(https://github.com/ADA-SITE-ENCE-3503/team-project-team-25)

### Part 1: Web Scraping
Using web scraping techniques, we extracted weather-related data into 8 initial columns. This provided the foundation for further analysis. Due to limitations in finding suitable websites that allowed web scraping for historical weather data with diverse columns, we utilized timeanddate.com as our primary source.

### Part 2: Data Cleaning and Exploratory Data Analysis (EDA)
1. **Data Cleaning:**
   - Removed non-numeric values next to numeric entries.
   - Replaced missing values with appropriate data to maintain dataset consistency.
   
2. **Feature Engineering:**
   - Added two new columns:
     - `temp_K`: Temperature converted to Kelvin.
     - `year`: Extracted the year from the dataset for better temporal analysis.

3. **Exploratory Data Analysis:**
   - Investigated the correlation between weather-related features.
   - Analyzed both numerical and categorical data to identify patterns and relationships within the dataset.

## Key Notes
- The scraped data initially consisted of 8 columns. Additional columns (`temp_K` and `year`) were added during the cleaning and EDA phase.
- Limited availability of websites offering historical weather data suitable for web scraping posed a challenge. Most available data focused on either future forecasts or the past week's data, which did not meet the project requirements.

## Tools and Technologies
- **Web Scraping:** Python libraries such as BeautifulSoup and requests.
- **Data Cleaning and EDA:** Python libraries such as pandas, NumPy, and matplotlib/seaborn for analysis and visualization.

Thank you for exploring our project! Feel free to reach out for any questions or further collaboration opportunities.
