# 微信运动步数修改助手 (Cloudflare Pages)

基于 Zepp Life（原小米运动）官方协议直推，支持国内手机直连，添加到 iPhone 主屏幕全屏运行。

## 目录结构
- `index.html`：针对手机优化的轻量前端界面（支持记住密码、快捷步数选择）
- `functions/api/update-steps.js`：Cloudflare Pages Functions，实现 Zepp Life V2 AES-128-CBC 认证与数据同步
