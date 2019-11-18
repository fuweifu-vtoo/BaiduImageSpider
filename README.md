#BaiduImageSpider

This is a package for searching for pictures on Baidu with keywords.

code copy from [](),But through this repository, you can download and install directly via pip.

##Usage
`pip install BaiduImageSpider` and
```python
import BaiduImageSpider
crawler = BaiduImageSpider.Crawler(0.1)
crawler.start('林俊杰', 2, 1)
```
Args:
- `sleep_time`: 0.1,代表每张图爬取的时间
- `word`: '林俊杰'，抓取的关键词
- `spider_page_num`: 需要抓取数据页数 总抓取图片数量为 页数x60
- `start_page`: 起始页数

## Examples
crawler.start('林俊杰', １, 1)
crawler.start('韩国美女', 2, 1)
crawler.start('红绿灯', 2, 1)
