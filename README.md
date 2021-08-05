# Web-scraping-using-selenium
Scraping Walmart reviews for a single product

Link scraped:
https://www.walmart.com/ip/Clorox-Disinfecting-Wipes-225-Count-Value-Pack-Crisp-Lemon-and-Fresh-Scent-3-Pack-75-Count-Each/14898365

Steps followed:
- Installed selenium
- Downloaded chromedriver
- Wrote scraper code in python, and named it to scraper.py

What does the Scraper do?
- opens the above url in Google chrome
- scrolls down to the review section
- clicks See All Reviews
- sorts reviews by most recent first
- gets all review blocks and then certain information from each review block
- clicks the next page and does the same till you see reviews from December 2020
- closes the browser and save the file
- everything above happens programmatically via scraper.py

output.csv contains:
- Review date
- Reviewer name
- Review title
- Review body or description
- Rating given by the user
