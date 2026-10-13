# TOYVERSE 潮玩积分俱乐部

王者主题收藏与积分俱乐部 H5 交互原型。使用原生 HTML、CSS 和 JavaScript，图片素材随源码提供。

## 部署到 Vercel

1. 在 Vercel 创建项目，导入 GitHub 仓库 `One-AI-Labs/wangzherongyao`。
2. Root Directory 保持仓库根目录，Framework Preset 选择 **Other**。
3. 仓库中的 `vercel.json` 已将 Output Directory 配置为 `dist`，并关闭安装和构建步骤，无需环境变量。
4. 点击 Deploy。

配置说明：https://vercel.com/docs/project-configuration/vercel-json

## 本地查看

直接打开 `dist/index.html`，或在安装了 Python 的环境中运行：

```sh
python -m http.server 8000 --directory dist
```

然后访问 `http://localhost:8000`。

## 文件说明

- `dist/index.html`：页面入口。
- `dist/app.js`、`dist/ux.js`：页面和交互逻辑。
- `dist/style.css`、`dist/luxury.css`：样式。
- `dist/assets/`：图片素材。
- `ASSET-SOURCES.md`：原项目的素材来源说明。

当前为前端演示，积分、登录、抽奖、兑换等使用模拟状态，没有真实账户、支付或后台服务。页面通过 URL hash 切换，无需服务器路由重写。

原始源码版本：`bfa8612eb1a9e5527966cf28d10199e53e15615b`。网站文件保持原样，仅增加 GitHub/Vercel 配置及本说明。
