# Amazon Web Scraper

This project is a collection of Python scripts that use Selenium and BeautifulSoup to scrape product details from Amazon and also handle pagination. 
The scripts extract product information such as title, price, rating, seller, availability, and total ratings from Amazon product listings and save the data to respective CSV files.

## Description

All the logic for scraping has been developed in the file `Logic_Building_BS4.ipynb`.

The file `Web_Scraping_Amazon_BS4.ipynb` generalizes the logic and iteratively scrapes product details for all products using `bs4` and `requests`.

The file `Web_Scraping_Amazon_Selenium.ipynb` generalizes the logic and iteratively scrapes product details for all products using `selenium`.

The file `Web_Scraping_Amazon_Selenium_Pagination.ipynb` generalizes the logic and iteratively scrapes product details for all products on the current page 
and also for next 2 pages, handling pagination using `selenium`.
## Getting Started

### Dependencies

Ensure you have the following installed:
* Python 3.7+
* Google Chrome (latest version)

Clone the Repository:
* `git clone https://github.com/marvelousmaaz04/web-scraping-amz.git`

### Installing

* `pip install -r requirements.txt`

### Executing the scripts (Windows)

```
1. Open any terminal
2. cd into web-scraping-amz
3. pip install -r requirements.txt
4. python -m notebook
5. Open the Jupyter notebooks separately.
6. To run the notebook, click on Kernel > Restart Kernel and Run all Cells.
7. Respective CSV files will be generated in the current directory. 
```

## Disclaimer

This repository is for educational purposes only. Scraping Amazon without permission may violate their Terms of Service. Use responsibly.
