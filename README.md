#  guba_distribute_crawler 分布式抓取东方财富股吧2000多支股票的信息

利用scrapy,mongodb,scrapy-redis,redis抓取[东方财富网股吧](http://guba.eastmoney.com/)的帖子数据

## 项目环境：
### 需要的软件
1. [scrapy 0.24.6](https://github.com/scrapy/scrapy/releases/tag/0.24.6) 
2. [mongodb 2.6.11](https://github.com/mongodb/mongo/releases/tag/r2.6.11)
3. redis
4. [scrapy-redis](https://github.com/rolando/scrapy-redis)

### 用到的python库：
1. pymongo
2. redis

项目实验主机使用windows+ubuntu，由于mongodb的原因，系统全部使用64bit


