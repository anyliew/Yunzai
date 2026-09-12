<div align="center">

# TRSS-Yunzai

Yunzai 应用端，支持多账号，支持协议端：OneBotv11、ComWeChat、GSUIDCore、ICQQ、QQBot、QQ频道、微信、KOOK、Telegram、Discord、OPQBot、Lagrange

## 安装教程

1. Git Clone 项目

```sh
git clone --depth 1 https://github.com/anyliew/Yunzai.git
```

</details>

2. 安装 [pnpm](https://pnpm.io/zh/installation) 和依赖

```sh
cd Yunzai
npm i -g pnpm
pnpm i
```

3. 前台运行

| 操作 | 命令 |
| ---- | ---- |
| 启动 | node . |
| 停止 | node . stop |
| 守护 | node . daemon |

4. 使用 [pm2](https://pm2.keymetrics.io) 后台运行

| 操作 | 命令 |
| ---- | ---- |
| 启动 | pnpm start |
| 停止 | pnpm stop |
| 日志 | pnpm log |

5. 开机自启

```sh
pnpm start
pnpm pm2 save
pnpm pm2 startup
```
