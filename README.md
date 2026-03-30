# blueingel.github.io

Guandan / 掼蛋 的产品介绍网站，部署于 GitHub Pages，供 Epic Developer Portal 审核使用。

A GitHub Pages website for the Guandan desktop card game, used as the Application Website and Privacy Policy URL for Epic Developer Portal review.

---

## 页面结构 / Pages

| 文件 / File | 说明 / Description |
|---|---|
| `index.html` | 首页 / Homepage |
| `privacy.html` | 隐私政策 / Privacy Policy |
| `404.html` | 自定义 404 页面 / Custom 404 page |
| `styles.css` | 共享样式表 / Shared stylesheet |
| `favicon.svg` | 网站图标 / Site favicon |

所有页面均采用**左右双栏布局**：左栏中文，右栏英文。在移动端自动切换为上下排列。

All pages use a **two-column bilingual layout**: Chinese on the left, English on the right. On mobile devices the columns stack vertically.

---

## 部署到 GitHub Pages / Deploying to GitHub Pages

1. 进入仓库 → **Settings** → **Pages**  
   Go to the repository → **Settings** → **Pages**

2. 在 **Source** 下选择分支（通常是 `main`）和根目录 `/`  
   Under **Source**, select the branch (usually `main`) and root folder `/`

3. 点击 **Save**，等待几分钟后网站即可访问  
   Click **Save** and wait a few minutes for the site to go live

4. 访问地址通常为：`https://<username>.github.io`  
   The site will be available at `https://<username>.github.io`

---

## 本地预览 / Local Preview

直接在浏览器中打开 `index.html` 即可预览，无需任何构建工具。

Open `index.html` directly in a browser – no build tools required.
