---
# Jekyll Front Matter
layout: post # 标识这是一个文章
title: 我的第一个 Web 爬虫项目
date: 2025-11-25 10:00:00 +0800 # 发布时间
categories: [项目, Python] # 重点：用于分类到“项目”板块
tags: [Python, Web Scraping, 数据分析]
# 开启评论
comments: true 
---

## 🎯 项目简介

这是一个使用 **Python** 和 **BeautifulSoup** 编写的 Web 爬虫，用于抓取某招聘网站的职位信息。

项目目标是为了分析不同城市的热门技术栈需求。

## 💡 实现细节

1.  **环境配置：** 使用 `pip install requests beautifulsoup4` 安装依赖。
2.  **数据抓取：** 核心代码如下：

```python
import requests
from bs4 import BeautifulSoup

url = '目标网站链接'
response = requests.get(url)
soup = BeautifulSoup(response.text, 'html.parser')
# ... 后续处理代码
