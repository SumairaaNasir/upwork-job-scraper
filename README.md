A Python project that uses Selenium to scrape job listings from Upwork. This scraper is designed to collect data such as job titles, hourly rates, experience levels, and estimated time for job listings related to data analysis. The script can handle pagination to scrape up to 10 pages of job listings.

**Features:**
- Extracts job titles, hourly rates, and experience levels.
- Handles pagination to scrape multiple pages of job listings.
- Automatically manages cookie consent pop-ups.
- Saves scraped data to a CSV file for further analysis.

**Requirements:**
- Python 3.x
- Selenium
- WebDriver (e.g., ChromeDriver)
- `pandas` library for handling CSV operations

**How to Use:**
1. Install required libraries:
   ```bash
   pip install selenium pandas
