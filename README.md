# NBA_Data_Scrape
Project Overview
Objective: The primary goal was to develop a robust data scraping tool that could efficiently extract regular season and playoff statistics for NBA players from 2015 to 2023. The project aimed to aggregate this data into a structured format for subsequent analysis and visualization.

Tools and Technologies
1.Python: Served as the core programming language for the project.
2.pandas: Utilized for data manipulation and analysis, enabling us to structure the scraped data into readable and analyzable tables.
3.requests: This library was essential for performing HTTP requests to NBA.com, retrieving the webpages that contain the necessary statistical data.

Implementation Details

1.Data Scraping Logic: A for loop was constructed to iterate through the years (2015-2023) and differentiate between regular season and playoff data.
The requests library fetched the web pages from NBA.com, while careful attention was paid to managing headers and session parameters to mimic a real user's browser behavior, reducing the risk of being blocked.

2.Data Extraction: Utilizing pandas, we parsed the HTML data, extracting relevant statistics based on predefined headers corresponding to the user's requirements, such as points per game, assists, rebounds, etc.

3.Time Delay Integration: To prevent the scraping process from being flagged and blocked by NBA.com’s anti-scraping systems, we incorporated a time delay mechanism within the loop. This ensured that the requests were spaced out, mimicking human browsing patterns.
