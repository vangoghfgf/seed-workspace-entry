<!-- seed-workspace-entry:v1 -->
# Seed 团队工作台入口

[打开工作台](https://vangoghfgf.github.io/seed-workspace-entry/)

此仓库仅包含公开的静态入口。页面会跳转至 HTTPS 工作台，使用团队账号与密码登录，无需安装 Tailscale。

业务数据、登录凭据及后台代码均不在本仓库。后台在服务电脑运行，服务电脑需保持联网、运行工作台和 cloudflared。服务离线时，本入口仍可打开，但无法进入工作台。

访问地址由 Cloudflare 临时 HTTPS 隧道提供；GitHub Pages 提供固定的跳转入口。隧道停止后当前地址失效，重启管理脚本会更新本入口。当前为两人团队试用方案；长期固定后台域名需要后续配置正式隧道。
