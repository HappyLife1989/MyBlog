---
title: Java学习概要
date: 2018-03-26 23:34:25
tags: Java
categories: Java
---

工作以后才零零散散的Java以应付工作。但是内心觉得别扭，别扭在于站得比较低，总是要垫着脚，伸长脖子才能看得稍微远点。为了学些思想，来个兴趣以进阶Java。  

Java编程和其它编程语言一样是一个解决问题的工具。解决问题往往是需要有方法的，好的方法高级点的说法就是艺术。对于像Java这样高级的编程语言，能让开发者更容易思考解决的问题办法。这里不强调Java编程语言的好处了，[网上太多了](http://www.runoob.com/java/java-intro.html)。谈谈接下来进一步学习Java的想法概要。    
- Java的知识点和其它许多编程语言一个套路：首先就是数据类型、简单运算、逻辑判断及函数。接下类和对象，这里两个基本功能要扎实（**数据结构与算法和设计模式**）。有了类和对象，根据JDK调用API可以处理更高级的数据（xml,json等），实现更复杂的处理过程（多线程，网络连接，数据库连接等）。接下来就学习好用的开源组件了，为节省生命不要自己再造轮子了，除非轮子不够好。最后就是技术架构的学习了（SpringMVC、MyBatis等）
- 对于一个程序或者系统来说DFX是不可忽视的：性能、安全、易维护（注释文档、LLT、HLT、组件化）   

学习应该是要有系统的，要有目的。接下来不断学习新知识点，将这些知识点串联起来做个小项目。在实践过程体会思想。   


### Java内部类
- 每个内部类都能独立的继承一个接口的实现，所以无论外部类是否已经继承了某个(接口的)实现，对于内部类都没有影响。内部类使得多继承的解决方案变得完整
- 方便将存在一定逻辑关系的类组织在一起，又可以对外界隐藏。高内聚
- 实现事件驱动系统
- 闭包是一种能被调用的对象，它保存了创建它的作用域的信息。

### Java并发
- 并发是更高级的编程了，不懂并发的程序员不能说是高级程序员。学习并发编程就像进入一个全新的领域。Web库类、Servlet、Swing天生的多线程。
- 并发要解决的问题大体为：“速度”和“设计可管理性”   
  - 并发时上下文切换是需要消耗cpu时间的。说到的速度是相对于阻塞而言。
  - 并发需要代价的，包含复杂性代价，但是这些代价与在程序设计、资源负载均衡以及用户方便使用方面的改进相比，微不足道。
- 并发是用于多处理器编程的基本工具。
