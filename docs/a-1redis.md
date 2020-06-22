## 1.1 redis

### 1.1.1 什么是redis?

redis 是一款基于内存的高速缓存数据库，全称为 Remote Dictionary Server（远程数据服务），存储的数据格式都是以键值对的形式存在。

### 1.1.2 为什么要用 redis？

* 数据都存储在内存中，访问速度快
* 具有5种数据结构，满足各种业务需求

### 1.1.3 介绍一下redis 的数据结构？

数据结构包括：String、list、set、zset、hash。

所有的数据结构都是由唯一的 key 字符串作为名称，只是 value数据不同。

**1.String**

最基本的数据结构，其内部实现类似于 ArrayList ，都是通过数组来进行存储，并且可以动态扩容。

**2.List**

相当于 LinkedList，所以插入和删除非常快。

