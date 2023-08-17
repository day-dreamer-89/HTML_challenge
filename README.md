# HTML_challenge
Project Name: Mars Web Scraping and Analysis
Part 1: Scrape Titles and Preview Text from Mars News
Part 2: Scrape and Analyse Mars Weather Data
Description
This project involves web scraping and data analysis related to Mars news articles and weather data. The goal is to extract information from specific websites, organize and store the scraped data, and perform analyses to gain insights into Mars-related information.

Deliverables
The project consists of two main deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
Files
Download the necessary files to get started from the following link: Module 11 Challenge files

Part 1: Scrape Titles and Preview Text from Mars News
In this part, we will scrape titles and preview text from Mars news articles. The process involves the following steps:

Open the Jupyter Notebook named part_1_mars_news.ipynb.
Use automated browsing to visit the Mars news site and inspect the page to identify the elements to scrape.
Create a Beautiful Soup object to extract text elements from the website.
Extract titles and preview text of the news articles, store them in Python dictionaries, and organize them in a list.
Optionally, save the scraped data in a JSON file.
Part 2: Scrape and Analyse Mars Weather Data
In this part, we will scrape and analyze Mars weather data. The process involves the following steps:

Open the Jupyter Notebook named part_2_mars_weather.ipynb.
Use automated browsing to visit the Mars Temperature Data Site (URL: https://static.bc-edx.com/data/web/mars_facts/temperature.html) and inspect the page to identify the elements to scrape.
Create a Beautiful Soup object to scrape data from the HTML table or use Pandas' read_html function.
Assemble the scraped data into a Pandas DataFrame with specific columns.
Examine and convert data types if necessary (datetime, int, float).
Analyze the dataset using Pandas functions to answer specific questions about Mars weather:
Number of months on Mars
Martian days worth of data in the dataset
Coldest and warmest months on Mars
Months with lowest and highest atmospheric pressure on Mars
Terrestrial days in a Martian year
Export the DataFrame to a CSV file.





