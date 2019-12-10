# BaiduImageSpider

This is a package for searching for pictures on Baidu with keywords.

code copy from [BaiduImageSpider](https://github.com/kong36088/BaiduImageSpider), But through this repository, you can download and install directly via pip.

## Usage
`pip install BaiduImageSpider` and
```python
import BaiduImageSpider
crawler = BaiduImageSpider.Crawler(0.1)
crawler.start('林俊杰', 2, 1)
```
Args:
- `sleep_time`: 0.1, This represents the time each picture is crawled.
- `word`: '林俊杰'，keyword,Support Chinese and English, or any text that can be searched on Baidu
- `spider_page_num`: Number of pages to be fetched Total number of images fetched Pages x60
- `start_page`: Start page

or install from source code:
```python
git clone https://github.com/fuweifu-vtoo/BaiduImageSpider.git
cd BaiduImageSpider
python setup.py install
```

## Examples
`crawler.start('林俊杰', １, 1)`
![](./images/林俊杰.png)
![](./images/林俊杰2.jpg)

`crawler.start('韩国美女', 2, 1)`
![](./images/韩国美女.png)
![](./images/韩国美女2.jpeg)

`crawler.start('hamburger', 2, 1)`
![](./images/hamburger.png)
![](./images/hamburger2.jpg)

## THANKS
[BaiduImageSpider](https://github.com/kong36088/BaiduImageSpider)
