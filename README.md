# data-collection-challenge
Challenge 11 of UoB Data Analytics bootcamp - data collection (web scrapping Mars data)

![Photo of Mars Rover](https://github.com/catisf/data-collection-challenge/blob/main/mars_rover.jpg)

# About the repository:
This repository contains:
- Jupyter Notebook ['part_1_mars_news.ipynb'](https://github.com/catisf/data-collection-challenge/blob/main/part_1_mars_news.ipynb), which scrapes news articles from [Mars Planet Science](https://static.bc-edx.com/data/web/mars_news/index.html)
- Jupyter Notebook ['part_2_mars_weather.ipynb'](https://github.com/catisf/data-collection-challenge/blob/main/part_2_mars_weather.ipynb) which scrapes a [table of Mars temperature data](https://static.bc-edx.com/data/web/mars_facts/temperature.html), analyses it and saves it in the csv file ['mars_data.csv'](https://github.com/catisf/data-collection-challenge/blob/main/mars_data.csv)


In order to run the repository you will need to install/import the following dependencies:
- splinter
- bs4 (BeautifulSoup)
- matplotlib
- pandas

# About the challenge:
## Objectives:
- Deliverable 1: Scrape titles and preview text from Mars news articles (['part_1_mars_news.ipynb'](https://github.com/catisf/data-collection-challenge/blob/main/part_1_mars_news.ipynb)).
- Deliverable 2: Scrape and analyze Mars weather data, which exists in a table (['part_2_mars_weather.ipynb'](https://github.com/catisf/data-collection-challenge/blob/main/part_2_mars_weather.ipynb)).
  
## Part 1: Scrape Titles and Preview Text from Mars News
- Using jupyter notebook ['part_1_mars_news.ipynb'](https://github.com/catisf/data-collection-challenge/blob/main/part_1_mars_news.ipynb), which scrapes news articles from [Mars Planet Science](https://static.bc-edx.com/data/web/mars_news/index.html):
  - Use automated browsing to visit the Mars news siteLinks to an external site. Inspect the page to identify which elements to scrape.
  - Create a Beautiful Soup object and use it to extract text elements from the website.
  - Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures.
 
## Part 2: Scrape and Analyze Mars Weather Data
- Using jupyter notebook ['part_2_mars_weather.ipynb'](https://github.com/catisf/data-collection-challenge/blob/main/part_2_mars_weather.ipynb):
  - Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape.
  - Create a Beautiful Soup object and use it to scrape the data in the HTML table
  - Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website
  - Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
  - Analyze the dataset by using Pandas functions to answer the following questions:
    - How many months exist on Mars?
    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    - What are the coldest and the warmest months on Mars (at the location of Curiosity)?
    - Which months have the lowest and the highest atmospheric pressure on Mars?
    - About how many terrestrial (Earth) days exist in a Martian year? 
  - Export the DataFrame to a CSV file.

