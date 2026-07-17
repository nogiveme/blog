---
title: AstroPaper 本地预览测试
author: Hanwei He
pubDatetime: 2026-07-17T08:00:00+08:00
featured: false
draft: false
tags:
  - Astro
  - Markdown
  - 测试
description: 用于验证 AstroPaper 博客文章、Markdown 渲染和本地预览环境的测试文档。
timezone: Asia/Shanghai
---

这是一篇用于验证 AstroPaper 项目环境的测试文章。如果你能在首页和文章列表中看到它，说明内容加载已经正常工作。

## Markdown 渲染检查

下面这些内容用于快速检查常见的 Markdown 语法：

- 无序列表
- **粗体文字**
- [Astro 官方网站](https://astro.build/)

> 本地开发环境运行正常后，就可以开始撰写自己的文章了。

### 代码块

```ts
const message: string = "Hello, AstroPaper!";
console.log(message);
```

## 下一步

后续文章可以继续放在 `src/content/posts/` 目录中，并复用本文顶部的 frontmatter 结构。
