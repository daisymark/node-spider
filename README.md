# node-spider

spider

### 介绍

------

​	主要用于练习，包括node、jade、 node-spider、redis、react 搭建起来一个可以抓取指定网址的所需的内容，并可视化抓取的数据，

1. 爬虫抓取数据使用 superagent cheerio (post: /spider?addr="")


1. 数据库采用 redis


1. 服务器使用express
2. 前端页面使用react 
3. 如直接输入抓取爬虫的网址 则使用jade模版返回可是界面(get: /spider?addr="")
