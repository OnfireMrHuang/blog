---
title: "你好，世界"
subtitle: ""
date: 2026-09-02
lastmod: 2026-09-02
draft: false
author: "Harry Huang"
authorLink: ""
description: "我的第一篇 Hugo + LoveIt 博客文章"
license: ""
images: []

tags: ["博客", "Hugo"]
categories: ["随笔"]

featuredImage: ""
featuredImagePreview: ""

hiddenFromHomePage: false
hiddenFromSearch: false
twemoji: false
lightgallery: true
ruby: true
fraction: true
fontawesome: true
linkToMarkdown: true
rssFullText: false

toc:
  enable: true
  auto: true
  keepStatic: false
code:
  copy: true
  maxShownLines: 50
math:
  enable: false
share:
  enable: true
comment:
  enable: true
seo:
  images: []
---

欢迎来到我的博客！这是使用 **Hugo** + **LoveIt** 主题搭建的第一篇文章。

<!--more-->

## 关于这个博客

- 基于 [Hugo](https://gohugo.io) 静态站点生成器
- 使用 [LoveIt](https://hugoloveit.com/zh-cn/) 主题
- 部署在 Vercel 上，免费、无需备案

## 一个代码示例

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

## 如何发布新文章

```bash
hugo new posts/我的新文章.md
# 编辑内容后，把 draft 改为 false
hugo server -D   # 本地预览
```

保持更新！
