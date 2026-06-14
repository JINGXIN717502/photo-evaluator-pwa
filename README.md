# 手机照片评价器

这是一个手机优先的 PWA 静态网页应用。部署到 HTTPS 静态托管后，手机只要有网就能打开，也可以添加到桌面当作 App 使用。

## 文件

- `index.html`：应用主页面，包含照片分析算法和界面。
- `manifest.webmanifest`：PWA 安装配置。
- `sw.js`：离线缓存。
- `icons/`：App 图标。

## 部署

把整个 `mobile-photo-evaluator` 文件夹上传到任意 HTTPS 静态托管服务即可，例如 GitHub Pages、Cloudflare Pages、Netlify、Vercel 或自己的服务器。

照片不会上传到服务器。网页只负责加载程序文件，照片分析在手机浏览器本地完成。
