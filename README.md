# Life OS 面试演示

[直接体验 Life OS](https://sylvia8866-dev.github.io/life-os-interview-demo/)

这是独立的静态作品集演示。无需注册；初始内容是模拟数据，访客操作只保存在各自浏览器的 localStorage。AI 解读标为“开发中”，没有接入在线模型。原项目源码、密钥和真实数据不在此公开仓库。

## 更新线上演示

1. 在私有的 `interview-demo` 源码目录修改页面。
2. 运行 `npm ci` 和 `npm run build -- --base=./`。
3. 将 `dist/` **里面的文件**更新到本仓库 `main` 分支根目录，保留 `.nojekyll`，然后提交并推送。
4. 在 **Settings → Pages** 查看部署状态；发布后用未登录浏览器检查首页、模块跳转和刷新。

GitHub Pages 从 `main` 分支根目录自动部署。`base=./` 用于项目站点的相对资源路径。
