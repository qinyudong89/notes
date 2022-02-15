### 何时使用读写分离
随着系统数据越来越多，打到数据库上的读写请求也越来越多，当单台数据库无法支撑这么多的并发请求时
### 如何处理过期读问题
* 强制走主库方案
* sleep 方案
* 判断主备无延迟方案
* 配合 semi-sync 方案
* 等主库位点方案
* 等GTID方案

Reference:

https://time.geekbang.org/column/article/77636
