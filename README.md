# Books Web Scraper 

A Python web scraping project that extracts book information from Books to Scrape using Requests and BeautifulSoup.

## Features

- Scrapes all 50 pages of the website
- Extracts book names
- Extracts book prices
- Extracts book URLs
- Converts relative URLs into clickable links
- Exports the collected data to Excel

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- OpenPyXL

## Output

The scraper generates an Excel file containing:

| Name | Link | Price |
|------|------|-------|
| A Light in the Attic | Clickable URL | £51.77 |

## How to Run

Install the required libraries:


pip install requests pandas beautifulsoup4 openpyxl
