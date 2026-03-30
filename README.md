# guandan

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

## 如何重命名仓库 / How to Rename the Repository

> **⚠️ 需要手动操作 / Manual action required**

将仓库名从 `blueingel.github.io` 改为 `guandan`，需要在 GitHub 网页上手动操作：

1. 进入仓库页面，点击 **Settings**（设置）  
   Go to the repository page and click **Settings**

2. 在 **General** 页面顶部找到 **Repository name** 字段，将名称改为 `guandan`  
   On the **General** page, find the **Repository name** field and change it to `guandan`

3. 点击 **Rename** 按钮确认  
   Click **Rename** to confirm

4. 重命名完成后，GitHub Pages 的网址将自动变为：  
   After renaming, the GitHub Pages URL will automatically become:

```
https://shupengzhu.github.io/guandan/
```

---

## 网站地址说明 / About the Site URL

> **重命名后的正确访问地址 / Correct URL after renaming:**

| 类型 | 仓库名规则 | 访问地址 |
|------|-----------|---------|
| 用户站点 (User Site) | 必须是 `shupengzhu.github.io` | `https://shupengzhu.github.io` |
| **项目站点 (Project Site)** | **任意名称**（本仓库即此类） | **`https://shupengzhu.github.io/guandan/`** |

**本网站的正确访问地址 / This site's URL:**

```
https://shupengzhu.github.io/guandan/
```

`https://shupengzhu.github.io`（不带路径）显示的是另一个仓库的内容，与本仓库无关。

`https://shupengzhu.github.io` (without a path) belongs to a different repository and is unrelated to this project.

---

## 部署到 GitHub Pages / Deploying to GitHub Pages

1. 进入仓库 → **Settings** → **Pages**  
   Go to the repository → **Settings** → **Pages**

2. 在 **Source** 下选择分支（通常是 `main`）和根目录 `/`  
   Under **Source**, select the branch (usually `main`) and root folder `/`

3. 点击 **Save**，等待几分钟后网站即可访问  
   Click **Save** and wait a few minutes for the site to go live

4. 网站访问地址（固定）：`https://shupengzhu.github.io/guandan/`  
   The site will be available at: `https://shupengzhu.github.io/guandan/`

---

## 本地预览 / Local Preview

直接在浏览器中打开 `index.html` 即可预览，无需任何构建工具。

Open `index.html` directly in a browser – no build tools required.
