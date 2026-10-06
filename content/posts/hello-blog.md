---
title: "第一篇文章：博客是怎么搭起来的"
date: 2026-10-06T09:00:00+08:00
draft: false
tags: ["博客", "Hugo"]
categories: ["技术"]
summary: "用 Hugo + PaperMod + GitHub Pages 从零搭建一个免费的个人博客，全程不到十分钟。"
---

欢迎来到我的博客 👋

这是第一篇文章，也是这个博客的"出生证明"。整个站点由以下部分组成：

- **[Hugo](https://gohugo.io/)** — 用 Go 写的静态站点生成器，没有任何运行时依赖；
- **[PaperMod](https://github.com/adityatelange/hugo-PaperMod)** — 简洁、响应式、支持暗色的主题；
- **[GitHub Pages](https://pages.github.com/)** — 免费托管，push 后由 GitHub Actions 自动构建发布。

## 写作流程

```bash
# 新建一篇文章
hugo new content posts/my-new-post.md

# 本地预览（含草稿）
hugo server --buildDrafts

# 推送后自动发布
git add . && git commit -m "new post" && git push
```

## 代码高亮测试

```python
def hello(name: str) -> str:
    return f"你好，{name}！"

print(hello("世界"))
```

## 接下来

以后会在这里记录技术实践、工程思考和学习笔记。敬请期待。
