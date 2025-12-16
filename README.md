# Python Web Scraper for Product Data

## Description
This is a professional Python web scraper designed to extract product information from any website. The scraper collects **product names** and **prices**, saves them to a **CSV file**, and includes advanced features like error handling, logging, and flexible CSS selectors.

This project demonstrates **Python programming, web scraping, file handling, and class-based design**, making it perfect for showcasing your skills to potential clients on Fiverr.

---

## Features
- Class-based modular design (`ProductScraper`)
- Flexible CSS selectors for product items, names, and prices
- Retry logic and timeout handling for network requests
- Logging with progress updates
- Safe extraction of product data to prevent errors
- Dynamic CSV filenames using current date
- Command-line arguments for URL, selectors, and CSV output
- Sample summary printed after scraping

---

## Technologies Used
- Python 3
- Requests library for HTTP requests
- BeautifulSoup for HTML parsing
- CSV for data export
- Logging module for progress and error reporting
- argparse for command-line interface

---

## How to Run
1. Install required libraries:
```bash
pip install requests beautifulsoup4

