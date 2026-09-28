# Autional

企业身份与访问管理（IAM）平台 —— 统一认证、授权、审计与合规。

## 产品站点

| 站点 | 地址 | 说明 |
| --- | --- | --- |
| 官网 | [www.autional.cn](https://www.autional.cn) | 产品介绍与快速开始 |
| 品牌门户 | [brand.autional.cn](https://brand.autional.cn) | 租户品牌选择入口（门户裸根无会话时的统一落点） |
| 演示入口 | [demo.autional.cn](https://demo.autional.cn) | 演示门户入口（Vercel 反向代理至内部源站，26 服务卡） |
| 身份认证 | [auth.autional.cn](https://auth.autional.cn) | 登录、注册、多因素认证与单点登录 |
| 用户中心 | [user.autional.cn](https://user.autional.cn) | 个人资料、安全设置、会话与授权管理 |
| 管理控制台 | [admin.autional.cn](https://admin.autional.cn) | 租户、用户、应用与策略的集中管理后台 |
| 安全中心 | [security.autional.cn](https://security.autional.cn) | 风险事件、登录审计与安全态势概览 |
| 平台控制台 | [platform.autional.cn](https://platform.autional.cn) | 平台级租户运营与全局配置 |
| 身份验证器 | [authenticator.autional.cn](https://authenticator.autional.cn) | 基于 TOTP 与通行密钥的两步验证 |
| 信任中心 | [trust.autional.cn](https://trust.autional.cn) | 安全实践、数据保护与合规建设进展说明 |
| 服务状态 | [status.autional.cn](https://status.autional.cn) | 各微服务的实时可用性与历史事件 |
| 开发者门户 | [developer.autional.cn](https://developer.autional.cn) | SDK、快速开始与接入指南 |
| 文档 | [docs.autional.cn](https://docs.autional.cn) | 产品与接入文档 |
| API 参考 | [reference.autional.cn](https://reference.autional.cn) | 各服务 API 规范 |
| API Wiki | [wiki.autional.cn](https://wiki.autional.cn) | API 使用说明 |
| API 入口 | [api.autional.cn](https://api.autional.cn) | 统一后端入口（BFF） |

## 仓库

每个站点对应一个独立仓库，推送至 `main` 分支后由 Vercel 自动部署。

| 分组 | 仓库 | 技术栈 |
| --- | --- | --- |
| 静态站 | [web](https://github.com/autional-cn/web) · [docs](https://github.com/autional-cn/docs) · [developer](https://github.com/autional-cn/developer) · [reference](https://github.com/autional-cn/reference) · [wiki](https://github.com/autional-cn/wiki) | Astro 5 + Tailwind CSS |
| 单页应用 | [auth](https://github.com/autional-cn/auth) · [admin](https://github.com/autional-cn/admin) · [user](https://github.com/autional-cn/user) · [security](https://github.com/autional-cn/security) · [status](https://github.com/autional-cn/status) · [trust](https://github.com/autional-cn/trust) · [platform](https://github.com/autional-cn/platform) · [authenticator](https://github.com/autional-cn/authenticator) · [brand](https://github.com/autional-cn/brand) | Vite + React 19 + TypeScript + Tailwind CSS |
| 后端入口 | [api](https://github.com/autional-cn/api) · [demo](https://github.com/autional-cn/demo) | Vercel 反向代理（BFF 转发 / 演示门户；Rewrites · `vercel.ts`） |

## 许可

[AGPL-3.0](https://github.com/autional-cn/.github/blob/main/LICENSE)

---

© 深圳市天艺网络技术有限公司 · 粤ICP备08016466号
