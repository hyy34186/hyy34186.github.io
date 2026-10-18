# 学术写作与生涯规划

个人博客，基于 [Hexo](https://hexo.io) + [Butterfly](https://butterfly.js.org) 主题，托管于 GitHub Pages。

## 在线地址

<https://hyy34186.github.io>

## 如何写文章

**方式一：命令新建**

```bash
npx hexo new "文章标题"
```

**方式二：手动创建**

在 `source/_posts/` 下新建文件，文件名格式为 `年-月-日-标题.md`，开头必须包含 front-matter：

```yaml
---
title: 文章标题
date: 2026-10-18 12:00:00
tags: [标签1, 标签2]
categories: [分类]
---
正文从这里开始（Markdown 语法）……
```

**发布**：写完直接 `git push` 即可，GitHub Actions 会自动构建并发布，约 1–3 分钟后生效。

## 本地预览

```bash
npm install
npm run server     # 浏览器打开 http://localhost:4000
```

## 目录结构

```
blog/
├── _config.yml              # Hexo 站点配置
├── _config.butterfly.yml    # 主题配置（菜单、搜索、页脚等）
├── source/_posts/           # 文章
├── source/about/            # 关于页
└── .github/workflows/       # 自动部署工作流
```
