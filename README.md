# NBA Data Scraper

## Overview
This project focuses on scraping NBA game data directly from NBA.com. It covers seasons from 2015 to the last completed season, capturing detailed game statistics and player performances. The primary goal is to gather comprehensive datasets for analysis and research purposes. Utilizing Python libraries such as `requests`, `numpy`, and `time`, we've designed a robust scraper that respects NBA.com's server load by implementing a time lag between requests.

## Features
- **Data Collection:** Scripts to scrape game statistics, player performances, and other relevant data from NBA.com.
- **Efficiency:** Utilizes the `requests` library for HTTP requests, `numpy` for data manipulation, and `time` to manage request intervals.
- **Respectful Scraping:** Includes a built-in time lag between consecutive requests to avoid overburdening NBA.com's servers and prevent getting blocked.
- **Data Range:** Covers all NBA seasons from 2015 through the last completed season.

## Requirements
- Python 3.8+
- requests
- numpy
- time (standard library, no installation required)

## Implementation Details
- **Requests Library:** Used for sending HTTP requests to NBA.com.
- **Time Lag:** A critical feature implemented using the `time.sleep()` function from the Python standard library, ensuring a respectful crawl rate.
- **Numpy:** Employed for efficient data manipulation and storage during the post-scraping phase.
