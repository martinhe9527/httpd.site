# httpd.site — Local HTTP & WebDAV Server

> 把你的手机/电脑一键变成 **本地 HTTP / WebDAV 服务器**。零配置、开箱即用，适合临时文件分享、跨设备同步与局域网服务演示。

## ✨ Features
- HTTP / WebDAV 服务：目录浏览、上传/下载、断点续传
- 一键分享：本地地址 + **二维码** 显示
- mDNS / 局域网直连：`http://httpd.local:PORT`
- 可选 HTTPS（自签或导入证书）
- 后台常驻 / 开机自启（Android）
- 轻量 UI，暗黑模式友好（Tailwind 风格）

## 🚀 Install
- **Android**：从 Releases / Google Play 安装（待上架）
- **Desktop / CLI**：规划中（欢迎关注 Roadmap）

## 📦 Usage（Android）
1. 打开 app，点击「Start」启动服务  
2. 在同一局域网其他设备上访问展示的 URL 或扫码二维码  
3. 需要 WebDAV 时，在客户端填入 `http://<ip>:<port>/`（或 `https://...`）

> 默认端口可在设置中修改；开启 HTTPS 需导入证书或生成自签证书。

## 🔐 Permissions（Android）
- `FOREGROUND_SERVICE` / `POST_NOTIFICATIONS`
- （可选）外部存储访问权限（用于选取共享目录）

## 🗺️ Roadmap
- [ ] 桌面 CLI（Win/macOS/Linux）
- [ ] 反向代理 / 端口映射助手
- [ ] 账户与访问令牌
- [ ] WebUI 上传进度与批量操作
- [ ] 插件：WebSocket/静态站点发布

## 🤝 Contributing
欢迎提 Issue / PR。请先阅读 `CONTRIBUTING.md`（待补充）。

## 📝 License
MIT © 2025 Yulin He
