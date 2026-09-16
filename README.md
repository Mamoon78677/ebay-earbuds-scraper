# eBay Earbuds Web Scraper

This is my first independent web scraping project built in Python. The script extracts product listings for earbuds from eBay and saves the collected data into a structured CSV file.

## Features
* Extracts product **Titles**
* Extracts product **Prices**
* Extracts **Product URLs**
* Extracts **Image Source Links**
* Bypasses strict anti-bot detection using custom Request Headers and browser Cookies.
* Saves all data automatically into `ebay_earbuds.csv`.

## Technologies Used
* **Python 3**
* **Requests**: To send HTTP requests to eBay.
* **BeautifulSoup4**: To parse the raw HTML structure.
* **CSV**: To export the data into a spreadsheet.

## What I Learned From This Project
* How to use browser **Developer Tools** (Network Tab) to analyze request headers.
* The concept of **Request Headers** (`User-Agent`, `Accept`) and how websites identify scripts.
* How **Cookies** function as session tokens to bypass `403 Forbidden` errors.
* How to safely handle data arrays and export them into tables using Python's built-in `csv` module.

## How to Run It
1. Clone the project to your computer.
2. Install the requirements:
   ```bash
   pip install requests beautifulsoup4 fake-useragent
   ```
3. Open the Jupyter Notebook file and run the cells.
