**#Yellow Pages Web Scraper**
This project contains a web scraper that extracts data from Yellow Pages for businesses in the manufacturing sector located in Dallas, TX. 
The code is written in Python and uses libraries like requests and BeautifulSoup to scrape information, as well as pandas to organize and export the data.

**#Overview**
The web scraper collects the following information for each business:

Company Name
Website
Contact Number
Street Address
Locality (City, State, ZIP)
Category (if available)

**Note: Email addresses are not available on Yellow Pages and therefore could not be included in this dataset.**

**How It Works**
Data Extraction: The code sends a request to the Yellow Pages URL and parses the HTML response.
Data Cleaning: Any business with missing data in the "Company Name" field is removed from the final dataset.
Data Export: The extracted data is organized into a structured format and saved as an Excel file (scraped_data_filtered.xlsx).
Usage
Clone this repository to your local machine.

**Install the required Python packages:**
pip install requests beautifulsoup4 pandas
Run the script:
python yellow_pages_scraper.py

After running, check your directory for scraped_data_filtered.xlsx, which will contain the cleaned data.
