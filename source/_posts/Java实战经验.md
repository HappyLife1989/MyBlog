---
title: Java实战经验
date: 2018-04-15 11:13:35
tags: Java
categories: Java
---

#### for循环和foreach循环比较--[参考](https://www.cnblogs.com/suneryong/p/6520442.html)
  - foreach 使用方便
  - 性能：需要循环数组结构的数据时，建议使用普通for循环，因为for循环采用下标访问，对于数组结构的数据来说，采用下标访问比较好。需要循环链表结构的数据时，一定不要使用普通for循环，这种做法很糟糕，数据量大的时候有可能会导致系统崩溃。  

#### 函数返回值
- 生成容器的函数不要返回null，返回空容器
```
private static java.util.List<String> getList(int limit) {		
		return Collections.EMPTY_LIST;		
	}
```
