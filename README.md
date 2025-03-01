# Mars Exploration: Web Scraping and Data Analysis

## Overview

This project aims to extract and analyze data from Mars-related websites to gain insights into Mars news and weather patterns. It is divided into two main deliverables: scraping news articles and analyzing Mars weather data.

## Project Goals

* Scrape and display the latest news titles and preview text from a Mars news website.
* Extract and analyze historical Mars weather data to understand temperature and atmospheric pressure trends.

## Repository Content

* `part_1_mars_news.ipynb`: Jupyter Notebook for scraping Mars news titles and preview text using `requests` and `BeautifulSoup`.
* `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data using `requests`, `BeautifulSoup`, `Pandas`, and `Matplotlib`. This notebook performs statistical analysis and visualization of temperature and atmospheric pressure trends.
* `mars_weather_data.csv`: CSV file containing the scraped Mars weather data. The CSV file contains the following columns: `id`, `terrestrial_date`, `sol`, `ls`, `month`, `min_temp`, `max_temp`, `pressure`.

## Running the Notebooks

1.  Ensure you have Python 3.x and the required libraries installed.
2.  Open and run the Jupyter Notebooks (`part_1_mars_news.ipynb` and `part_2_mars_weather.ipynb`).
3.  Ensure that the `mars_weather_data.csv` file is in the same directory as `part_2_mars_weather.ipynb`.

## Sources of Help

* MODULE 11 ACTION ITEMS: Emailed by Camille Bolos, Sr Student Success Advisor.
* Copilot AI.
* YouTube videos.
