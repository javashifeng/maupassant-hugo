---
title: "什么是GC Roots"
date: 2019-04-01T00:07:47+08:00
draft: false
---

# GC Root
我们常说的GC root，特指垃圾回收器的对象，GC会收集不是GC root且没有被gc root引用的对象。
一个对象可以有多个gc root，有以下几种：