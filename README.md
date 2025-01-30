# Amazon Web Scraper

This project is a collection of Python scripts that use Selenium and BeautifulSoup to scrape product details from Amazon and also handle pagination. 
The scripts extract product information such as title, price, rating, seller, availability, and total ratings from Amazon product listings.

## Description

All the logic for scraping has been developed in the file `Logic_Building_BS4.ipynb`.

The file `Web_Scraping_Amazon_BS4.ipynb` generalizes the logic and iteratively scrapes product details for all products using `bs4` and `requests`.

The file `Web_Scraping_Amazon_Selenium.ipynb` generalizes the logic and iteratively scrapes product details for all products using `selenium`.

The file `Web_Scraping_Amazon_Selenium_Pagination.ipynb` generalizes the logic and iteratively scrapes product details for all products on the current page 
and also for next 2 pages, handling pagination using `selenium`.
## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [dbader](https://github.com/dbader/readme-template)
* [zenorocha](https://gist.github.com/zenorocha/4526327)
* [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
