+++
title = "Redis集群"
date = 2019-04-14T17:54:02+08:00
draft = false
tags = ["web","golang"]
categories = ["Redis"]
+++

# Redis集群方案
本篇文章简单介绍五种方案：

* 官方cluster方案

* twemproxy代理方案

* 哨兵模式

* codis

* 客户端分片

## 官方cluster方案

从redis 3.0版本开始支持redis-cluster集群，redis-cluster采用无中心结构，每个节点保存数据和整个集群状态，每个节点都和其他节点连接。redis-cluster是一种服务端分片技术。

redis-cluster架构图

