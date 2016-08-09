## Redis
Redis是一个开源的，先进的 key-value 存储可用于构建高性能，可扩展的 Web 应用程序的解决方案。Redis官方网网站是：http://www.redis.io/，如下：<br> 
![image](https://github.com/silence940109/Redis/blob/master/image/1-160F20T40K25.png)<br>

* Redis 有三个主要使其有别于其它很多竞争对手的特点：
* Redis是完全在内存中保存数据的数据库，使用磁盘只是为了持久性目的； 
* Redis相比许多键值数据存储系统有相对丰富的数据类型； 
* Redis可以将数据复制到任意数量的从服务器中；

##Redis优点
* 异常快速 : Redis是非常快的，每秒可以执行大约110000设置操作，81000个/每秒的读取操作。

* 支持丰富的数据类型 : Redis支持最大多数开发人员已经知道如列表，集合，可排序集合，哈希等数据类型。

* 这使得在应用中很容易解决的各种问题，因为我们知道哪些问题处理使用哪种数据类型更好解决。
操作都是原子的 : 所有 Redis 的操作都是原子，从而确保当两个客户同时访问 Redis 服务器得到的是更新后的值（最新值）。

* MultiUtility工具：Redis是一个多功能实用工具，可以在很多如：缓存，消息传递队列中使用（Redis原生支持发布/订阅），在应用程序中，如：Web应用程序会话，网站页面点击数等任何短暂的数据； 