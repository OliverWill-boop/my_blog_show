# volcano's blog

![GitHub](https://img.shields.io/github/license/volcano/volcano-blog?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/volcano/volcano-blog?style=flat-square)

个人技术博客，记录学习心得、项目经验和技术分享。

## 📍 博客地址

[https://volcano-blog.netlify.app/](https://volcano-blog.netlify.app/)

## ✨ 功能特点

- 🎨 响应式设计，适配各种设备
- 📱 现代化界面，简洁美观
- 🌙 支持深色/浅色模式切换
- 🔍 站内搜索功能
- 📂 文章分类与标签管理
- 📊 文章归档功能
- 💬 评论系统集成
- 🌐 多语言支持
- 🚀 快速加载速度

## 🛠 技术栈

- **框架**: [Hugo](https://gohugo.io/) - 静态网站生成器
- **主题**: [hugo-theme-stack](https://github.com/CaiJimmy/hugo-theme-stack)
- **部署**: [Netlify](https://www.netlify.com/)
- **CI/CD**: GitHub Actions
- **样式**: SCSS
- **脚本**: TypeScript

## 🚀 快速开始

### 环境要求

- Hugo v0.80.0 或更高版本
- Git

### 本地开发

1. 克隆仓库

```bash
git clone https://github.com/volcano/volcano-blog.git
cd volcano-blog
```

2. 启动开发服务器

```bash
hugo server -D
```

3. 访问本地预览

打开浏览器访问 [http://localhost:1313](http://localhost:1313)

### 构建生产版本

```bash
hugo --minify
```

构建产物将生成在 `public` 目录。

## 📁 目录结构

```
.
├── .github/           # GitHub Actions 配置
├── archetypes/        # 内容模板
├── content/           # 博客内容
│   ├── categories/    # 分类
│   ├── page/          # 独立页面
│   └── post/          # 博客文章
├── layouts/           # 页面布局
├── public/            # 构建输出
├── resources/         # 资源文件
├── static/            # 静态文件
├── themes/            # 主题
└── hugo.yaml          # Hugo 配置
```

## 🌍 内容管理

### 新建文章

```bash
hugo new post/文章标题.md
```

### 文章格式

```yaml
---
title: "文章标题"
date: 2024-01-01T00:00:00+08:00
draft: false
categories:
  - 分类1
  - 分类2
tags:
  - 标签1
  - 标签2
summary: "文章摘要"
---

文章内容...
```

## 📝 部署方式

本博客使用 GitHub Actions 自动部署到 Netlify：

1. 推送代码到 GitHub
2. GitHub Actions 自动构建
3. 部署到 Netlify
4. 访问 [https://volcano-blog.netlify.app/](https://volcano-blog.netlify.app/)

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request 来改进这个博客。

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 📞 联系方式

- 博客: [https://volcano-blog.netlify.app/](https://volcano-blog.netlify.app/)
- GitHub: [@volcano](https://github.com/volcano)

---

> 持续更新中，欢迎关注！🌟