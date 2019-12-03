+++
title: "CentOS修改时区为东八区"
date: 2019-12-03T16:32:32+08:00
draft: false
tags: ["CentOS"]
categories: ["Linux"]
comments: true
share: true
+++


#### 修改时区为上海

```language-shell
vim /etc/sysconfig/clock
ZONE="Asia/Shanghai"
```

#### 建立软链接

```language-shell
rm /etc/localtime
ln -s /usr/share/zoneinfo/Asia/Shanghai /etc/localtime
```

#### 设置ntp同步

```language-shell
yum install ntpdate
添加任务crontab -e
20 02 * * * /usr/sbin/ntpdate time.nuri.net
20 22 * * * /usr/sbin/ntpdate ntp1.aliyun.com
写入bios
hwclock -w
```
