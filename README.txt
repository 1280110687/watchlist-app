追番管理器 PWA 使用说明

不要再直接把 HTML 当手机本地文件长期打开。
正确方式：部署到一个 HTTPS 静态站点，再从浏览器“添加到主屏幕”。

目录中的文件：
- index.html
- manifest.json
- sw.js

可部署到：
- GitHub Pages
- Netlify Drop
- Cloudflare Pages
- Vercel

部署后优点：
- 数据按站点 origin 稳定保存
- 可离线打开
- 可添加到手机桌面
- 不依赖“浏览器本地标签页还活着”

注意：
- 换浏览器 / 清除站点数据 / 重装系统，数据仍可能丢失
- 建议定期点击“导出备份”
