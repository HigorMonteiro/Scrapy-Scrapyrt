# Scrapy and Scrapyrt

how to create your own API from (almost) any website

## Getting Started
```
$ https://github.com/HigorMonteiro/Scrapy-Scrapyrt.git
$ cd Scrapy-Scrapyrt
$ virtualenv -p python3.6 .env
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
