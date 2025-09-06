# ATW 串焊机 4级解锁 — PWA 版（v5）

部署到 GitHub Pages / Cloudflare Pages 后，用手机浏览器访问并 **添加到主屏幕**，从桌面图标打开即可更稳定地实现**打开即聚焦并弹出数字键盘**。

- `index.html`：PWA + 自动聚焦 + 自动计算
- `manifest.webmanifest`：PWA 清单
- `sw.js`：Service Worker 缓存
- `icons/icon-192.png`, `icons/icon-512.png`：图标
- `.nojekyll`：用于 GitHub Pages

> 提醒：相机功能需要 HTTPS 或 `localhost`。如有脚本错误，会显示在页面“错误”区域。
