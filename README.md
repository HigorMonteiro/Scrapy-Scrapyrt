# Scrapy and Scrapyrt

How to create your own API from (almost) any website.
# About the Project 

We will scrape the URL: https://coinmarketcap.com/all/views/all/. It contains information about cryptocurrencies such as their current prices, their price variations, etc.

## Getting Started
```
$ git clone https://github.com/HigorMonteiro/Scrapy-Scrapyrt.git
$ cd Scrapy-Scrapyrt
$ virtualenv -p python3.6 .env
$ source .env/bin/activate
$ pip install -r requirements.txt
$ scrapy crawl coin -o coin.json
$ scrapyrt -p 3000
$ curl http://localhost:3000/crawl.json?start_requests=true&spider_name=coin
```
### Prerequisites

```
$ python 3.x.x
$ virtualenv
```

## Authors

* **Higor Monteiro** - *Initial work* - [HigorMonteiro](https://github.com/HigorMonteiro)
