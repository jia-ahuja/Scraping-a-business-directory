# Web Scraping Project: Swiss Manufacturing Companies

## Overview
This Jupyter notebook contains a Python script for scraping information about manufacturing companies in Switzerland from the D&B (Dun & Bradstreet) business directory website. The script uses proxy servers and various techniques to avoid detection and maintain a stable connection while scraping.

## Features
- Proxy usage for IP rotation
- User-agent and header randomization
- Parsing of company details including name, location, and sales information
- Data organization into a pandas DataFrame

## Dependencies
- requests
- pandas
- BeautifulSoup (from bs4)
- time
- tqdm
- random
- pprint

## Usage
1. Set up your proxy credentials in the "Getting proxies" section. I used BrightData for getting proxies.
2. Run the cells in order.
3. The main scraping loop is in the last cell, where you can adjust the range of pages to scrape.

## Code Structure
1. Importing dependencies
2. Setting up and testing proxy connection
3. Function to organize scraped raw data
4. Function to scrape data from a single page
5. Main scraping loop

## Notes
- The script uses various techniques to mimic human browsing behavior, including random delays and header variations.
- The current version scrapes pages 1 to 20. Adjust the range in the final cell as needed.

## Disclaimer
Web scraping may be against the terms of service of some websites. Use this script responsibly and ensure you have the right to collect the data you're targeting.

## Author
[Jiya Ahuja]
