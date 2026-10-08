# Autional

企业身份与访问管理（IAM）平台 —— 统一认证、授权、审计与合规。

## 门户

| 门户 | 地址 | 说明 |
| --- | --- | --- |
| 身份认证 | [auth.autional.cn](https://auth.autional.cn) | 登录、注册、多因素认证与单点登录 |
| 用户中心 | [user.autional.cn](https://user.autional.cn) | 个人资料、安全设置、会话与授权管理（需登录） |
| 管理控制台 | [admin.autional.cn](https://admin.autional.cn) | 租户、用户、应用与策略的集中管理后台（需登录） |
| 安全中心 | [security.autional.cn](https://security.autional.cn) | 风险事件、登录审计与安全态势概览（需登录） |
| 平台控制台 | [platform.autional.cn](https://platform.autional.cn) | 平台级租户运营与全局配置（需登录） |
| 身份验证器 | [authenticator.autional.cn](https://authenticator.autional.cn) | 基于 TOTP 与通行密钥的两步验证（需登录） |
| 品牌门户 | [brand.autional.cn](https://brand.autional.cn) | 租户品牌选择入口（门户裸根无会话时的统一落点） |
| 信任中心 | [trust.autional.cn](https://trust.autional.cn) | 安全实践、数据保护与合规建设进展说明 |
| 服务状态 | [status.autional.cn](https://status.autional.cn) | 各微服务的实时可用性与历史事件 |

## 站点

| 站点 | 地址 | 说明 |
| --- | --- | --- |
| 官网 | [www.autional.cn](https://www.autional.cn) | 产品介绍与快速开始 |
| 演示入口 | [demo.autional.cn](https://demo.autional.cn) | 演示门户（Vercel 反向代理，27 服务卡） |
| 文档 | [docs.autional.cn](https://docs.autional.cn) | 产品与接入文档 |
| 开发者门户 | [developer.autional.cn](https://developer.autional.cn) | SDK、快速开始与接入指南 |
| API 参考 | [reference.autional.cn](https://reference.autional.cn) | 各服务 API 规范（OpenAPI 3.0 交互式） |
| API Wiki | [wiki.autional.cn](https://wiki.autional.cn) | API 使用说明 |
| API 入口 | [api.autional.cn](https://api.autional.cn) | 统一后端入口（BFF） |

## 仓库

站点源仓已统一至 [autional](https://github.com/autional) 组织（本组织站仓已归档退役）；推送 autional 侧仓 `main` 分支由 Vercel 自动部署。

| 分组 | 仓库 | 技术栈 |
| --- | --- | --- |
| 门户 | [auth](https://github.com/autional-cn/auth) · [user](https://github.com/autional-cn/user) · [admin](https://github.com/autional-cn/admin) · [security](https://github.com/autional-cn/security) · [platform](https://github.com/autional-cn/platform) · [authenticator](https://github.com/autional-cn/authenticator) · [brand](https://github.com/autional-cn/brand) · [trust](https://github.com/autional-cn/trust) · [status](https://github.com/autional-cn/status) | Vite + React 19 + TypeScript + Tailwind CSS |
| 静态站 | [web](https://github.com/autional-cn/web) · [docs](https://github.com/autional-cn/docs) · [developer](https://github.com/autional-cn/developer) · [reference](https://github.com/autional-cn/reference) · [wiki](https://github.com/autional-cn/wiki) | Astro 5 + Tailwind CSS |
| 基础设施 | [api](https://github.com/autional-cn/api) · [demo](https://github.com/autional-cn/demo) · [cdn](https://github.com/autional-cn/cdn) | Vercel 反向代理与静态资源 CDN |
| 设计系统 | [ui](https://github.com/autional/ui) | 设计令牌、品牌资产与站点规范（canonical） |

## 许可

开源组件（门户、设计系统、文档）：[AGPL-3.0](https://github.com/autional-cn/.github/blob/main/LICENSE) · SDK 软件包：MIT · 核心身份服务：商业授权

---

© Autional
