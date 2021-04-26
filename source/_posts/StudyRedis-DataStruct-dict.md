```yaml
title: [TODO] redis 学习 基础数据结构篇 之 dict
date: 2021-04-27 00:35:23
description: ["redis 基础数据结构 - 字典。"]
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
  - dict
  - rehash
  - 渐进式 rehesh
```

> 基于redis 6.2.1

# dict（字典）

TODO 字典的定义

## dict的实现

hash算法  - SipHash 1-2

## hash冲突解决（链地址法）

rehash 和 渐进式 rehash

## dict重要API

# 总结

rehash
