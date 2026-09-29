# 高炜彤 · 作品集

新媒体运营 / 视觉设计 / 游戏内容运营（实习 · 上海）· 东华大学 网络与新媒体

在线地址：**https://116gwt116.github.io/gwt116/**

## 目录结构

```
index.html            导览首页（作品集入口，手写 HTML/CSS）
dhu-admissions/       项目 01 · 东华招生网（单页招生网站）
  ├── index.html
  ├── images/
  └── vendor/         GSAP + ScrollTrigger
.github/workflows/    自动发布：推 main → 同步到 gh-pages
```

## 怎么加一个新项目

1. 在本仓库根目录新建英文名文件夹，例如 `xingyin/`
2. 把项目文件放进去，**入口文件名必须是 `index.html`**（子目录相对路径照常写 `images/xx.png`）
3. 在根目录 `index.html` 的作品列表里加一行（把 `plain` 行改成带 `<a href="xingyin/">` 的可点击行）
4. 推送到 `main` 分支 —— GitHub Actions 会自动同步到发布分支，1-2 分钟后线上生效

访问地址规则：`https://116gwt116.github.io/gwt116/<文件夹名>/`

## 发布机制（重要）

- GitHub Pages 的发布分支是 **`gh-pages`**（当初推 `gh-pages` 分支触发了自动启用）
- 仓库根目录的 `.github/workflows/pages.yml` 会在每次推送 `main` 时，**自动把 main 同步到 gh-pages**，所以平时只需维护 `main`

## 注意

- **纯前端项目才能直接跑**：需要后端/服务器的项目（例如要启动 Python 服务的文字模拟器）无法在 GitHub Pages 上运行，需要导出静态版，或改放截图 / 演示视频
- 页面尽量不依赖外部 CDN（被墙环境会掉字体/脚本）；必须依赖时写好回退

---

*本站为个人作品集，内容用于学习与作品展示。*
