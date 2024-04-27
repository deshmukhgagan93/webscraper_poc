# Web Scraper :- Stock Data POC

This Python script allows you to scrape stock data for one or more stock and save the data to a CSV file.

## Features

- **Scraping**: Scrapes various stock data including regular market price, market changes, post-market data, and more.
- **Dynamic Content Handling**: Handles consent overlays and waits for dynamic content to load before scraping.
- **Headless Mode**: Supports running in headless mode for automated execution without opening a browser window.
- **Command-Line Interface**: Accepts stock names as command-line arguments for easy integration with other scripts or automation workflows.
- **Output**: Saves scraped data to a CSV file with a header row containing the field names.

## Requirements

- Python 3.x
- Selenium
- Chrome WebDriver
- Chrome Browser
