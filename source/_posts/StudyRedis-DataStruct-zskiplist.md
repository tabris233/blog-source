---
title: "【TODO】Redis 学习 基础数据结构篇 之 跳表(skiplist)"
date: 2021-05-04 20:10:58
description: ["Redis 基础数据结构 - 跳表。"]
toc: true
author: tabris

# 图片推荐使用图床(腾讯云、七牛云、又拍云等)来做图片的路径.如:http://xxx.com/xxx.jpg
img:

# 如果top值为true,则会是首页推荐文章
top: false

# 如果要对文章设置阅读验证密码的话,就可以在设置password的值,该值必须是用SHA256加密后的密码,防止被他人识破
password:

# 本文章是否开启mathjax，且需要在主题的_config.yml文件中也需要开启才行
mathjax: false
summary:
categories:
  - redis
tags:
  - redis
  - skiplist
  - 跳表
---

[TOC]

> 基于 [Redis 6.2.1]([redis/redis at 6.2.1 (github.com)](https://github.com/redis/redis/tree/6.2.1))

# 跳表

​		跳表（skiplist）是一种有序的数据结构，它通过在每个节点中维持多个指向其他节点的指针，从而达到快速访问的目的。

​		跳跃表支持平均$O(log N)$, 最坏$O(N)$复杂度的节点查找，还可以通过顺序性操作来批量处理节点。 

## 跳表的结构

跳表既然是叫XX表，本质上还是链表。

## 增删改查

