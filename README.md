# Mikexujunrui.github.io

徐俊瑞（Junrui Xu）的个人主页 · https://mikexujunrui.github.io/

纯静态站：单页 `index.html` + 手写博客，无框架、无构建步骤，直接由 GitHub Pages 托管。

## 结构

```
├── index.html                    # 主页（简介 / 动态 / 项目 / 博客 / 教育 / 经历 / 荣誉）
├── blog/                         # 博客文章（手写 HTML，每篇一个文件）
│   └── 2026-11-21-hello.html
└── assets/
    └── avatar.png
```

## 如何新增一篇博客

1. 复制 `blog/` 里任意一篇作为模板，改正文与日期；
2. 在 `index.html` 的 `Blog` 区块加一行链接。

## 本地预览

直接双击 `index.html`，或：

```bash
python -m http.server 8000
# 打开 http://localhost:8000
```

## 许可

页面内容（文字）© 徐俊瑞。设计参考了 Jon Barron / Tianxing Chen 风格的学术主页布局，CSS 为手写实现。
