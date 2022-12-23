# Web Scrapping Financial News
We often have plenty of unstructured data available for free on the internet. Some of this data may be useful for combining with other structured or unstructured data available in the organization.

The project aims to automate the process of gathering unstructured (raw HTML) finance data using Python library BeautifulSoup & transform into structured data JSON and save as CSV
## Objectives :

1. Automate the process of gathering unstructured data which is in the form of raw HTML.

2. Learn to web scrap Financial News of specific listed companies on the Stock Market.

3. Use BeautifulSoup4 Python library for web scraping - Install, Exception Handling, Advanced HTML Parsing.

4. How to traverse a single domain to fetch data from many HTML pages.

5. Process gathered (scrapped) data and transform it into structured format JSON and save as CSV.

## Set up and Installation:
```bash
pip install --upgrade pip
pip install -r requirements.txt
```
Create a sub-directory 'content' in project-directory to save CSV files
## This is what a general DIY web scraping process looks like:

1. Identify the target website
2. Collect URLs of the pages where you want to extract data from
3. Make a request to these URLs to get the HTML of the page
4. Use locators to find the data in the HTML
5. Save the data in a JSON or CSV file or some other structured format
