# Claire · Swiss Skill PPT

这是一个单文件 HTML 横向 PPT，介绍如何安装和调用 Codex Skill。

## 本地查看

直接打开 `index.html` 即可。使用 `← →` 翻页，`B` 切换静态模式，`ESC` 查看索引。

## 自动检查与部署

每次推送到 `main` 时，GitHub Actions 会：

1. 检查 Swiss deck 的 8 页版式和 `data-layout`。
2. 确认入口文件与本地动效文件存在。
3. 上传 GitHub Pages artifact。
4. 自动部署到 GitHub Pages。

部署地址通常是：

`https://gogoclaire.github.io/Claire/`
