# CodeAlpha Web Scraping Project

## Project Overview
This project is completed as part of the CodeAlpha Data Analytics Internship.

The aim of this project is to scrape book data from a website using Python and save the collected data into a CSV file.

## Website Used
Books to Scrape  
https://books.toscrape.com/

## Data Collected
The project collects the following information:

- Book Title
- Price
- Rating

## Tools and Libraries Used
- Python
- requests
- BeautifulSoup
- pandas
- VS Code

## Files in This Project
- `web_scraping.py` - Python file used to scrape data from the website
- `books_data.csv` - CSV file containing the scraped book data
- `README.md` - Project explanation file

## How the Project Works
1. The Python script sends a request to the website.
2. BeautifulSoup reads the HTML content of the page.
3. The script extracts book title, price, and rating.
4. The extracted data is stored in a pandas DataFrame.
5. The final data is saved into a CSV file named `books_data.csv`.

## How to Run This Project
Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas
