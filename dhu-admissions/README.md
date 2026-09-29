# 东华招生网 · 网页作品

东华大学招生信息页面的网页作品 —— 内容策划、信息编排与页面更新维护。

## 这是什么

一个**单文件 HTML** 招生宣传网页：整站信息集中在一个 `index.html` 里，二级页面（关于 / 学科 / 校园 / 招生 / 就业等）通过模板注入的方式切换，配合 GSAP 滚动动效完成浏览节奏。

- 内容策划与信息编排：高炜彤
- 技术：原生 HTML / CSS / JavaScript + GSAP ScrollTrigger + React 组件（CDN 引入）
- 图片与素材：东华大学官方公开素材

## 怎么打开

**本地打开**
1. 下载本仓库（或 clone）
2. 双击 `index.html`（建议 Chrome / Edge / Safari）
3. 注意：`index.html` 必须和 `images/`、`vendor/` 放在同一层，否则图片和动画不显示

**在线预览**
GitHub Pages 部署后可通过 `https://<用户名>.github.io/dhu-admissions-site/` 访问。

## 需要联网

页面引用了在线字体和 React 组件库。断网时页面仍可打开，但字体会回退为系统默认字体。

## 目录结构

```
index.html    网页主文件
images/       图片素材
vendor/       动画库（GSAP + ScrollTrigger）
README.md     本文件
```

## 操作提示

- 上下滚动浏览完整页面，页面有滚动触发的动画
- 顶部导航可进入各二级页面（关于 / 学科 / 校园 / 招生等）

---

*本仓库为个人作品集项目之一，仅用于学习与作品展示。*
