---
title: 'Hexo server 开启错误'
date: 2019-12-02 08:11:00
tags:
---

## 问题描述
4000端口被占用

![](https://raw.githubusercontent.com/qpyghb/GraphBed/master/img/20191202081531.png)

## 查看占用并关闭端口
```
sudo lsof -i :4000
sudo kill -9 1929
sudo kill -9 11058
```
![](https://raw.githubusercontent.com/qpyghb/GraphBed/master/img/20191202081013.png)