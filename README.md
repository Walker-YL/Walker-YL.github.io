# walker-yl's Blog

> 一个20年供应链管理老兵的个人博客，记录管理思考、技术分享与人生感悟。

## 🎯 博客简介

这是一个基于 Hexo + Butterfly 主题的个人博客，主要分享：

- 🏭 **管理思考**：供应链优化、团队管理、行业洞察
- 💻 **技术分享**：Python、Excel、数据分析等效率工具
- 🌱 **人生随笔**：职业成长、生活感悟、读书笔记

**博客地址**: https://walker-yl.github.io

## 🚀 快速开始

### 本地预览

```bash
# 安装依赖
npm install

# 本地预览
npx hexo server
```

访问 http://localhost:4000 查看博客

### 创建新文章

```bash
npx hexo new "文章标题"
```

### 构建和部署

```bash
# 清理并构建
npx hexo clean
npx hexo generate

# 部署到 GitHub Pages
npx hexo deploy
```

## 📁 项目结构

```
.
├── .github/              # GitHub 配置
│   └── workflows/        # GitHub Actions 工作流
├── source/               # 博客内容
│   ├── _posts/          # 文章目录
│   ├── about/           # 关于我页面
│   ├── contact/         # 联系我页面
│   ├── categories/      # 分类页面
│   └── archives/        # 归档页面
├── themes/              # 主题目录
├── _config.yml          # Hexo 主配置
├── _config.butterfly.yml # Butterfly 主题配置
└── package.json         # NPM 配置
```

## ✨ 主题特色

- 🎨 **Butterfly 主题**：简洁美观，支持深色模式
- 📱 **响应式设计**：完美适配各种设备
- 🔍 **本地搜索**：快速查找文章
- 📊 **文章统计**：阅读时间、字数统计
- 🎯 **TOC 目录**：方便导航长文章
- 🌙 **深色模式**：支持自动切换

## 🎨 自定义配置

### 修改个人信息

编辑 `_config.yml` 文件中的网站信息：

```yaml
title: walker-yl | 20年供应链管理
author: walker-yl
language: zh-CN
```

### 修改主题配置

编辑 `_config.butterfly.yml` 文件来自定义主题样式、导航栏、侧边栏等。

## 📝 写作模板

```markdown
---
title: 文章标题
date: 2025-05-16 10:00:00
tags:
  - 标签1
  - 标签2
categories:
  - 分类名
cover: /img/cover.jpg
---

正文内容...

<!-- more -->

继续阅读...
```

## 🔧 技术栈

- **框架**: Hexo 8.x
- **主题**: Butterfly 5.x
- **渲染器**: pug + stylus
- **部署**: GitHub Pages
- **CI/CD**: GitHub Actions

## 🤝 贡献

欢迎提出 Issue 或 Pull Request！

## 📄 许可证

MIT License

---

*感谢你的来访！*
