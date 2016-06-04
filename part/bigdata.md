# python就业班-大数据

## 服务器应用（4d）

### MongoDB非关系型数据库开发(2d)

+ Mongo简介
	1. MongoDB特点
	2. MongoDB的应用场景、案例
	3. MongoDB和sql的对应关系
	4. MongoDB安装
	5. Ubuntu下的安装文档
+ 文档和集合
	1. Mongo常用数据类型
	2. 创建、删除数据库
	3. MongoDB增、查、删、改
	4. MongoDB索引
	5. MongoDB聚集
	6. MongoDB副本集
	7. 查询分析
+ 复制
	* MongoDB复制原理
+ 集群
	* 搭建集群
+ 实例应用	
	* python操作MongoDB基本语法
	 
### Memcached缓存服务器开发(0.5d)
	+ Memcached部署和安装
	+ Memcache的特征
	+ 内置存储方式
	+ Memcached参数详解
	+ 性能测试
+ 实例应用	
	* python开发Memcached应用
	
### 消息队列RabbitMQ(0.5d)	
	+ 配置安装
	+ 消息应答
	+ 发布订阅
	+ 关键字绑定队列
	+ 关键字模糊匹配队列
+ 实例应用	
	* python操作Memcached基本语法
	
### Redis缓存服务器开发(1d)
	+ Redis基本操作
	+ Redis数据类型
	+ Hash（字典）
	+ List（队列）
	+ Set（集合）
	+ Sorted Set（有序集合）
	+ 订阅、发布系统
	+ 事务-Transaction
	+ Redis配置文件
	+ 持久化
	+ RDB方式、AOF方式
	+ Redis实现快照的过程
	+ Redis性能测试
+ 实例应用	
	* python操作Redis基本语法

## 云计算和大数据(10d)

###	爬虫入门(3d)
	1. 网络爬虫基本原理及工作流程
	2. 常用的请求报头（Header、Content-Type）、响应报头
	3. 常用请求方式（GET、POST）
	5. 代理IP
	6. Cookies处理
	7. 页面解析、提取结构化数据
		7.1 CSS选择器
		7.2 XPath表达式
		7.3 正则表达式
	8. gzip压缩
	9. 常用解决Forbidden爬虫方法
	10. 常用网页分析解析辅助工具Fidder
	11. 网页编码格式和自动识别
	12. 验证码处理
	13. 多线程并发抓取
	+ 实例应用
		1. 熟练使用Fidder调试工具
		2. 登陆新浪微博		
			2.1 学习使用selenium自动化测试工具登陆	
			2.2 获取cookie	
		3. 抓取百度贴吧（涉及知识点）		
			3.1 urllib2、urllib库的使用	
			3.2 网页编码、正则表达式、Xpath语法	
			3.3 多线程编写	
			3.4 gzip压缩

### 爬虫Scrapy框架(3d)
+ 配置安装
+ 基本概念
	1. 爬取对象Items
	2. 选择器(Selectors)
	3. Scrapy终端(Scrapy shell)
	4. 数据填充(Item Loaders)
	5. Item Pipeline（数据后处理）
	6. Spider中间件(Middleware)
	7. Jobs: 暂停，恢复爬虫
	8. 部署Scrapyd
+ 实例应用	
	1. 实现腾讯招聘网站信息抓取（http://hr.tencent.com/position.php）
	2. 实现百度贴吧信息抓取（http://tieba.baidu.com/f?ie=utf-8&kw=%E5%BE%B7%E7%94%B2）
	
### 分布式集群Pyspider框架(4d)
+ 配置安装
+ 基本概念
	1.框架介绍
	2. HTML和CSS选择器
	3. AJAX和HTTP
	4. 使用PhantomJS渲染带JS的页面
	5. 部署
+ 实例应用
	1. 实现易果生鲜垂直电商信息抓取（http://www.yiguo.com/)	
	2. 实现去哪儿网酒店信息抓取（http://hotel.qunar.com/)
	
	