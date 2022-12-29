
# Read Me

Kalibr scraping is crawler that aims data from Kalibr to xlsx, this scraper works in about 1 - 5 sec / page depends on the internet & driver.

## Run Locally

Clone the project

```bash
  git clone https://github.com/haydarmiezanie/KalibrCrawler
```

Install dependencies

```bash
  pip install selenium
  pip install pandas
  pip install beautifulsoup
```

Start the scraper

```bash
  python -m kalibr_crawler [start_page] [end_page]
```
Example :

```bash
  python -m kalibr_crawler 1 36
```
## Scraper Flow

![image](https://user-images.githubusercontent.com/39428898/209944925-023ad1dc-b589-46b7-8eb3-d38b582cba10.png)


## Limitation

This crawler is only example how to crawl data from Kalibr. This method work's very efficient.

## Authors

- [Haydar Miezanie](https://github.com/haydarmiezanie)

