---
title: "部署流程"
date: 2025-06-25T15:34:30-04:00
categories:
  - Blog
tags:
  - Post Formats
  - notice
---

远程安装方法
远程主题类似于基于 Gem 的主题，但不需要更改或列入白名单，因此非常适合使用 GitHub Pages 托管的站点
创建/替换 的内容 为以下内容：Gemfile
```html
source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins
```
添加到 .jekyll-include-cacheplugins_config.yml
通过运行以下 Bundler 命令来获取和更新捆绑的 Gem：

```html
bundle
```

添加到您的文件。删除任何其他 或 条目。remote_theme: "mmistakes/minimal-mistakes@4.27.1"_config.ymltheme:remote_theme:
