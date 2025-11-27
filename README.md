# 🕸️ Web Scraper Using Python (Requests + BeautifulSoup)

This project is a simple and customizable web scraping tool built using Python’s requests and BeautifulSoup libraries. It extracts data from any webpage using CSS selectors and saves the results in a structured format.

# 📌 Features

Scrapes data from any URL using a user-defined CSS selector

Uses custom headers to mimic real browser requests

Handles HTTP errors gracefully

Extracts and cleans text content from HTML elements

Saves scraped data to CSV using Pandas

# 🛠️ Technologies Used

Python

Requests

BeautifulSoup (bs4)

Pandas

# 🚀 How It Works

Send a GET request to the target website

Parse the HTML using BeautifulSoup

Select elements based on a CSS selector

Extract and clean text values

Save results to book_titles.csv

# 📄 Example
url = "http://books.toscrape.com/"
selector = "article.product_pod h3 a"
book_titles = scrape_website(url, selector)

# 📂 Output

Prints list of scraped items

Saves extracted text into a CSV file

# 🔍 Use Cases

Product listings

Blog titles

Headlines extraction

Automated data collection for analysis
