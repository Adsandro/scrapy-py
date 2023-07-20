
# Scrapy
**Description:**
This repository contains two Python spiders implemented using Scrapy, a web scraping framework. The spiders are designed to extract data from different websites: IMDb (Internet Movie Database) and BoardGameGeek.

**1. IMDb Spider:**
**Name: imdb**
- **Purpose:** This spider scrapes the IMDb's "Top Rated Movies" chart and extracts movie titles, release years, and IMDb ratings.
- **Website:** IMDb Top Rated Movies

**Usage:**
Install Scrapy by running pip install scrapy in your Python environment.
Run the spider by executing scrapy runspider imdb_spider.py in the terminal.
The spider will fetch data from the IMDb website and store it in a JSON file.

**2. BoardGameGeek Spider:**
**Name: game**
- **Purpose:** This spider scrapes the BoardGameGeek website to retrieve board game rankings, names, and average ratings.
- **Website:** BoardGameGeek Browse Board Games

**Usage:**
Ensure Scrapy is installed by running pip install scrapy in your Python environment.
Run the spider with scrapy runspider game_spider.py in the terminal.
The spider will crawl the BoardGameGeek website, extracting relevant data and saving it to a JSON file.

**Note:**
Web scraping should be performed ethically and responsibly, adhering to the website's terms of service and policies.
The spiders are provided as examples for educational purposes and to demonstrate Scrapy's capabilities.
The spiders' behavior might change if the website's structure or layout is modified, requiring adjustments to the scraping logic.

**Author:**
Adsandro Carvalho / adsandroxerd@gmail.com
