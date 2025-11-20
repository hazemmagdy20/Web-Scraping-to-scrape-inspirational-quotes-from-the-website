# Web-Scraping-to-scrape-inspirational-quotes-from-the-website
This script scrapes inspirational quotes from the website, parses the HTML content, extracts relevant information and saves the data to a quotes.csv file for later use.

**Steps to extract**

**1-Send an HTTP Request:** Use the requests library to send a request to the webpage URL and get the HTML content in response.

**2-Parse the HTML Content:** Use a parser like html.parser or html5lib to convert the raw HTML into a structured format (parse tree).

**3-Extract Data:** Use BeautifulSoup to navigate the parse tree and extract the required data using tags, classes, or IDs.


**Result**

We obtain a csv file named as quotes qhich include the following columns:

**theme**

**image_url**

**lines**

**auther**

