scrapy爬取豆瓣电影top250
新建项目 明确目标 制作爬虫 存储内容 
1.新建scrapy项目：
scrapy startproject name
生成spider：
scrapy genspider name_spider+域名
2.明确目标
  确定要抓取的数据， xpath匹配要抓取的数据，
3 编写爬虫
  xpath制定爬虫要抓取的数据
4 存储数据：
  导出csv，json。或存储到mongodb
tips: 中间件中编写完规则后 在setting中启用