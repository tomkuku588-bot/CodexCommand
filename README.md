# Code指挥舱合规文档

这个目录用于部署 Code指挥舱的静态合规文档，包含中英文隐私政策和用户协议。

## 文件

- `index.html`：合规文档入口页
- `privacy-policy.html`：隐私政策，包含中文和英文版本
- `user-agreement.html`：用户协议，包含中文和英文版本
- `permission-rationale.md`：权限说明
- `assets/legal.css`：静态页面样式

## 部署地址

仓库关联为：

```text
git@github.com:tomkuku588-bot/CodexCommand.git
```

启用 GitHub Pages 后，预计访问地址为：

```text
合规入口：https://tomkuku588-bot.github.io/CodexCommand/
隐私政策：https://tomkuku588-bot.github.io/CodexCommand/privacy-policy.html
用户协议：https://tomkuku588-bot.github.io/CodexCommand/user-agreement.html
```

## 部署方式

当前部署采用 `gh-pages` 分支根目录发布静态文件。更新页面后执行：

```bash
git push origin main
git push origin main:gh-pages
```

若 Pages 首次访问仍为 404，请在 GitHub 仓库 Settings - Pages 中选择：

```text
Source: Deploy from a branch
Branch: gh-pages
Folder: / (root)
```

## 上架前复核

- 当前应用名称：`Code指挥舱`
- 当前包名：`com.xmgod.codexcommand`
- 当前版本：`1.0.0`
- 当前运营者/开发者：`xmgod`
- 当前联系邮箱：`tomkuku588@gmail.com`
- 当前应用不申请系统敏感权限，不接入网络，不包含账号体系、第三方登录、广告、统计、推送、支付或云同步。

如上架主体名称、企业名称或联系方式变化，请在提交前同步替换 HTML 和权限说明中的主体信息。
