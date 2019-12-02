---
title: "面试考点梳理"
date: 2019-04-14T17:54:02+08:00
draft: false
tags: ["java","面试"]
categories: ["面试"]
---

# Java面试考点梳理

本文是根据我的面试经验，为大家整理Java程序猿面试所需的知识体系。

## 第一部分：计算机基础

互联网大厂都相当重视程序员的基本功，也就是计算机基础知识。一个程序员能走多远、爬多高，很大程度上取决于基本功是否扎实。对于应届生而言，大都比较缺乏实战项目经验，虽然会有一定的项目经验，但这些课程设计、实验室项目的质量与公司实际的项目有着巨大的差距。因此，基础知识便成为面试考量的一大重点，而且基础扎实的程序员可塑性比较高，做什么都能比较容易快速上手。

计算机基础包含如下几门课程，相信计算机专业的同学肯定都已经学过。但互联网公司面试的考点可能和你们期末考试的考点有一些不同，我都做了整理。

### 1. 计算机网络

大学课程中的计算机网络一般都按照OSI七层参考模型介绍，然而由于互联网公司的特性，他们更加关注日常开发所涉及到的传输层和应用层，所以需要重点掌握传输层和应用层中所涉及到的所有知识点。

【考点】

传输层的作用

传输层复用和分用的含义

传输层和网络层的区别

UDP协议的特点

UDP协议的报文结构

TCP协议的特点

TCP协议的报文结构

TCP三次握手过程

TCP四次挥手过程

TCP可靠传输是如何实现的

停止等待协议

滑动窗口协议

TCP的流量控制

TCP拥塞控制

HTTP协议

HTTP工作流程

HTTP请求格式

HTTP 1.1中的8种请求方式

HTTP响应格式

HTTP中重要的请求头和响应头字段

HTTP常用状态码及其含义

HTTPS协议

HTTPS协议与HTTP协议的区别

HTTPS协议的工作流程

【资料整理】

[计算机网络传输层知识点全覆盖-大闲人柴毛毛的博客](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F55006347)

[HTTP详解(1)-工作原理](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fhguisu%2Farticle%2Fdetails%2F8680808)

[HTTP详解(2)-请求、响应、缓存](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fhguisu%2Farticle%2Fdetails%2F8683290)

[HTTP详解(3)-http1.0 和http1.1 区别](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fhguisu%2Farticle%2Fdetails%2F8608888)

[图解 HTTPS 通信过程](https://link.juejin.im/?target=http%3A%2F%2Fwww.liqwei.com%2Fnetwork%2Fprotocol%2F2012%2F906.shtml)

### 2. 数据结构

熟练掌握数据结构是程序员最最最基本的素养，在实际开发中选择合适的数据结构将极大影响程序的效率。面试官一般并不会直接问数据结构的问题，而是通过出一些包含数据结构的算法题来考察你对数据结构的理解程度以及在实际项目中是否能够灵活应用。你可以通过刷算法题来提升这部分能力，推荐《剑指offer》和《程序员面试金典》（注意是金典！）。很多公司的算法题库都选自这两本书。

当然，刷这两本书的目的并不是让你死记硬背题目，题目千变万化，面试官可以随意改变。刷算法题最重要的是培养解决问题的思路和解决实际问题的能力。在刷题的过程中要多多总结，再次强调，切忌死记硬背！

### 3. 算法

和数据结构一样，算法一般也通过具体的算法题来考察，你也可以通过刷《剑指offer》和《程序员面试金典》中的算法题来提高这方面的技能。但在刷这些算法题之前，你需要掌握几类基础的算法，并理解他们解决问题的思路（这才是最为关键的）。这些算法我已经在下面整理。

[一般背包问题](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F69357819)

[最佳合并模式](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F69367274)

[最小代价生成树](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F69663285)

[迪杰斯特拉算法](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F69666748)

[佛洛依德算法](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F69681130)

[最长公共子序列](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F69788300)

[0/1背包问题](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F69789040)

[多段图问题](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F70053196)

[n皇后问题](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F70142539)

[BFS](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F70140712)

[DFS](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F70140712)

### 4. 操作系统

【考点】

操作系统的四个特性。

操作系统的主要功能。

进程的有哪几种状态，状态转换图，及导致转换的事件。

进程与线程的区别。

进程通信的几种方式。

进程同步的几种方式

用户态和核心态的区别。

死锁的概念，导致死锁的原因。

导致死锁的四个必要条件。

处理死锁的四个方式。

预防死锁的方法、避免死锁的方法。

进程调度算法。

内存连续分配方式采用的几种算法及各自优劣。

基本分页储存管理方式。

基本分段储存管理方式。

分段分页方式的比较各自优缺点。

几种页面置换算法，会算所需换页数

虚拟内存的定义及实现方式。

【资料整理】

[操作系统面试重难点总结](https://link.juejin.im/?target=https%3A%2F%2Fwww.jianshu.com%2Fp%2Fd254b138de03)

[常见面试题整理--操作系统篇（每位开发者必备）](https://link.juejin.im/?target=https%3A%2F%2Fzhuanlan.zhihu.com%2Fp%2F23755202)

### 5. 数据库

【考点】

什么是索引？

索引的分类

索引的优缺点分析

何时需要使用索引？何时无需使用索引？

什么是事务？

事务的四大特性

数据库三大范式

数据库有哪些表连接？

【资料整理】

[数据库索引全面解析](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F60968248)

[数据库事务详解](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F60968283)

[数据库三大范式](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F60968300)

[常见面试题整理--数据库篇（每位开发者必备）](https://link.juejin.im/?target=https%3A%2F%2Fzhuanlan.zhihu.com%2Fp%2F23713529)

## 第二部分：Java

作为一名合格的Java程序员，仅了解如何使用Java是远远不够的。你能够熟练使用Java只能说明你已经成为一名合格的码农，能够利用Java实现某些功能。而公司作为盈利机构，需要用最少的资源实现效益最大化，这就需要程序员具备高质量代码的能力，而能否写出高质量代码取决于你对技术背后原理的理解程度。只有在理解Java背后的原理，你才能根据Java的特性，写出更加高效的代码。这在实际业务中是非常有价值的事情。互联网大厂服务海量用户，更加注重系统的性能，也更加注重程序员对原理的理解。

关于Java的基础知识和如何使用，这里我就不提了，随便一本Java书籍都有详细的介绍。这里我整理了Java原理性的知识点，这些知识点将会成为你面试的加分项。

### 1. Java虚拟机

【考点】

Java虚拟机内存模型特点和作用

程序计数器

Java虚拟机栈

本地方法区

堆

方法区

对象创建过程

对象访问过程

对象的内存结构

垃圾收集算法

如何判定哪些对象需要回收？

对象内存分配策略

分配担保机制

垃圾收集器的比较

Class文件结构

类加载的时机

类加载过程

双亲委派模型

【知识点资源整理】

[深入理解JVM(一)——JVM内存模型](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51170118)

[深入理解JVM(二)——揭开HotSpot对象创建的奥秘](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51190801)

[深入理解JVM(三)——垃圾收集策略详解](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51189318)

[深入理解JVM(四)——对象内存的分配策略](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51192448)

[深入理解JVM(五)——HotSpot垃圾收集器详解](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51199767)

[深入理解JVM(六)——JVM性能调优实战](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51232463)

[深入理解JVM(七)——Class文件结构](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51245055)

[深入理解JVM(八)——类加载的时机](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51251430)

[深入理解JVM(九)——类加载的过程](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F51254858)

[深入理解JVM(十)——类加载器](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F58145910)

### 2. Java并发编程

【考点】

什么是死锁？如何避免死锁？

什么是重排序？

volatile有哪些特性？

什么是内存可见性？

volatile为什么能够保证内存可见性？

中断机制

线程通信有哪些方式？

线程池的作用？

ThreadPoolExecutor如何使用？

如何设置线程池的大小？

如何保证线程安全？

JDK 1.6哪些对锁做了哪些优化？

【知识点资源整理】

[Java并发编程的艺术(一)——并发编程需要注意的问题](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54233279)

[Java并发编程的艺术(二)——重排序](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54285658)

[Java并发编程的艺术(三)——volatile](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54290526)

[Java并发编程的艺术(四)——线程的状态](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54292463)

[Java并发编程的艺术(五)——中断](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54313661)

[Java并发编程的艺术(六)——线程间的通信](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54341405)

[Java并发编程的艺术(七)——Executors](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54580157)

[Java并发编程的艺术(八)——闭锁、同步屏障、信号量详解](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54580082)

[Java并发编程的艺术(九)——批量获取多条线程的执行结果](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54580710)

[Java并发编程的艺术(十)——线程池(1)](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F56673564)

[Java并发编程的艺术(十一)——线程池(2)](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F56676897)

[Java并发编程的艺术(十二)——线程安全](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F58323471)

[Java并发编程的艺术(十三)——锁优化](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F58598307)

[Java并发容器大合集](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fu010425776%2Farticle%2Fdetails%2F54890215)

### 3. Java 容器考点及资料整理

[Java 集合系列01之 总体框架](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308498.html)

[Java 集合系列02之 Collection架构](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308513.html)

[Java 集合系列03之 ArrayList详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308556.html)

[Java 集合系列04之 fail-fast总结(通过ArrayList来说明fail-fast的原理、解决办法)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308762.html)

[Java 集合系列05之 LinkedList详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308807.html)

[Java 集合系列06之 Vector详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308833.html)

[Java 集合系列07之 Stack详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308852.html)

[Java 集合系列08之 List总结(LinkedList, ArrayList等使用场景和性能分析)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308900.html)

[Java 集合系列09之 Map架构](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3308931.html)

[Java 集合系列10之 HashMap详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3310835.html)

[Java 集合系列11之 Hashtable详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3310887.html)

[Java 集合系列12之 TreeMap详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3310928.html)

[Java 集合系列13之 WeakHashMap详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3311092.html)

[Java 集合系列14之 Map总结(HashMap, Hashtable, TreeMap, WeakHashMap等使用场景)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3311126.html)

[Java 集合系列15之 Set架构](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3311136.html)

[Java 集合系列16之 HashSet详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3311252.html)

[Java 集合系列17之 TreeSet详细介绍(源码解析)和使用示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3311268.html)

[Java 集合系列18之 Iterator和Enumeration比较](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2F3311275.html)

### 4. Java IO 考点及资料整理

[java io系列02之 ByteArrayInputStream的简介,源码分析和示例(包括InputStream)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_02.html)

[java io系列03之 ByteArrayOutputStream的简介,源码分析和示例(包括OutputStream)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_03.html)

[java io系列04之 管道(PipedOutputStream和PipedInputStream)的简介,源码分析和示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_04.html)

[java io系列05之 ObjectInputStream 和 ObjectOutputStream](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_05.html)

[java io系列06之 序列化总结(Serializable 和 Externalizable)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_06.html)

[java io系列07之 FileInputStream和FileOutputStream](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_07.html)

[java io系列08之 File总结](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_08.html)

[java io系列09之 FileDescriptor总结](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_09.html)

[java io系列10之 FilterInputStream](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_10.html)

[java io系列11之 FilterOutputStream](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_11.html)

[java io系列12之 BufferedInputStream(缓冲输入流)的认知、源码和示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_12.html)

[java io系列13之 BufferedOutputStream(缓冲输出流)的认知、源码和示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_13.html)

[java io系列14之 DataInputStream(数据输入流)的认知、源码和示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_14.html)

[java io系列15之 DataOutputStream(数据输出流)的认知、源码和示例](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_15.html)

[java io系列16之 PrintStream(打印输出流)详解](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_16.html)

[java io系列17之 System.out.println("hello world")原理](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_17.html)

[java io系列18之 CharArrayReader(字符数组输入流)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_18.html)

[java io系列19之 CharArrayWriter(字符数组输出流)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_19.html)

[java io系列20之 PipedReader和PipedWriter](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_20.html)

[java io系列21之 InputStreamReader和OutputStreamWriter](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_21.html)

[java io系列22之 FileReader和FileWriter](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_22.html)

[java io系列23之 BufferedReader(字符缓冲输入流)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_23.html)

[java io系列24之 BufferedWriter(字符缓冲输出流)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_24.html)

[java io系列25之 PrintWriter (字符打印输出流)](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_25.html)

[java io系列26之 RandomAccessFile](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fskywang12345%2Fp%2Fio_26.html)

[深入分析 Java I/O 的工作机制](https://link.juejin.im/?target=https%3A%2F%2Fwww.ibm.com%2Fdeveloperworks%2Fcn%2Fjava%2Fj-lo-javaio%2Findex.html)

### 5. Java其他知识点汇总

[深入理解java异常处理机制](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fhguisu%2Farticle%2Fdetails%2F6155636)

[Java中关于WeakReference和WeakHashMap的理解](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2FSkyar%2Fp%2F5962253.html)

[HashMap在并发下可能出现的问题分析](https://link.juejin.im/?target=https%3A%2F%2Fyq.aliyun.com%2Farticles%2F38431)

[深入分析ConcurrentHashMap](https://link.juejin.im/?target=http%3A%2F%2Fwww.infoq.com%2Fcn%2Farticles%2FConcurrentHashMap%2F)

[Java中的Copy-On-Write容器](https://link.juejin.im/?target=https%3A%2F%2Fmy.oschina.net%2Fxianggao%2Fblog%2F390390)

[Java中有关Null的9件事](https://link.juejin.im/?target=http%3A%2F%2Fwww.importnew.com%2F14229.html)

[浅谈常用的几种web攻击方式](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2FEchoer%2Fp%2F4781664.html)

[Collections.sort源码分析](https://link.juejin.im/?target=https%3A%2F%2Fzhuanlan.zhihu.com%2Fp%2F22293328)

[Java8系列之重新认识HashMap](https://link.juejin.im/?target=http%3A%2F%2Fwww.importnew.com%2F20386.html)

[深入理解Java中的String](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Fxiaoxi%2Fp%2F6036701.html)

[Arrays.sort()你应该知道的事](https://link.juejin.im/?target=http%3A%2F%2Fwww.importnew.com%2F8952.html)

[细数JDK里的设计模式](https://link.juejin.im/?target=http%3A%2F%2Fwww.cnblogs.com%2Ftinyking%2Fp%2F5938547.html)

[Java单例模式中双重检查锁的问题](https://link.juejin.im/?target=http%3A%2F%2Fblog.csdn.net%2Fchenchaofuck1%2Farticle%2Fdetails%2F51702129)
