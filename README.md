# Codex指挥舱合规文档

这个目录用于部署 Codex指挥舱的静态合规文档，包含中英文隐私政策和用户协议。

## 文件

- `index.html`：合规文档入口页
- `privacy-policy.html`：隐私政策，包含中文和英文版本
- `user-agreement.html`：用户协议，包含中文和英文版本
- `permission-rationale.md`：权限说明
- `assets/legal.css`：静态页面样式
- `.github/workflows/pages.yml`：GitHub Pages 自动部署工作流

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

推送到 `main` 分支后，GitHub Actions 会把根目录中的静态页面发布到 GitHub Pages。若仓库首次使用 Pages，请在 GitHub 仓库的 Settings - Pages 中确认发布源为 GitHub Actions。

## 上架前复核

- 当前应用名称：`Codex指挥舱`
- 当前包名：`com.xmgod.codexcommand`
- 当前版本：`1.0.0`
- 当前运营者/开发者：`xmgod`
- 当前联系邮箱：`tomkuku588@gmail.com`
- 当前应用不申请系统敏感权限，不接入网络，不包含账号体系、第三方登录、广告、统计、推送、支付或云同步。

如上架主体名称、企业名称或联系方式变化，请在提交前同步替换 HTML 和权限说明中的主体信息。
