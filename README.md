# Hulu204's Blog

这是我的个人博客，使用 Jekyll 构建，托管在 GitHub Pages。

## 本地运行

```bash
# 安装依赖
bundle install

# 启动本地服务器
bundle exec jekyll serve

# 访问 http://localhost:4000
```

## 发布文章

在 `_posts` 目录下创建新文件，文件名格式：`YYYY-MM-DD-title.md`

文章开头需要包含 Front Matter：

```markdown
---
layout: post
title: "文章标题"
date: YYYY-MM-DD HH:MM:SS +0800
categories: 分类
---

文章内容...
```

## 部署

推送到 GitHub 后，GitHub Pages 会自动构建和部署。

访问地址：https://hulu204.github.io
