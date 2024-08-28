# A simple Web Scraping Project

This project is a web scraping application that collects information about products on Mercado Libre, such as price and rating, and stores this data in an Excel file. This can be useful for tracking prices and ratings of products you are interested in on Mercado Libre.

## Requirements

Make sure you have the following Python libraries installed before running the project:
- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): For parsing the HTML content of the web page.
- [Requests](https://docs.python-requests.org/en/latest/): For making HTTP requests to the Mercado Libre page.
- [Pandas](https://pandas.pydata.org/): For manipulating and saving data to an Excel file.

## Database
In this case, it is a 3-column table that only scrapes the first page and analyzes the prices of the recommended products.
- **Title**
- **Price**
- **Calification**

## Additional
But this is not enough to understand the reasons behind the prices and conduct an analysis for the best price/quality option and thanks to a recent update to the website, it is no longer necessary to use Selenium for full scraping due to hidden content that previously required a user click to reveal. Nevertheless, I will continue scraping only the first page of recommended products.<br>
I will attempt to build a table with the following columns:
- Brand
- Series
- Processor
- Graphics card
- RAM
- Storage
- Screen size
