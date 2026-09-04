# 推房开放平台

推房开放平台面向租房、二手房、商办、写字楼、商铺等业务场景提供开放 API，帮助合作方将业务系统接入推房助手。

[![接口文档](https://img.shields.io/badge/接口文档-推房开放平台-1677ff)](https://tuifang-open-wiki.yumeng.work/)
[![开放平台](https://img.shields.io/badge/开放平台-登录入口-1677ff)](https://tuifang-open.yumeng.work/open-platform/platforms)

## 你可以接入什么

- 租房、二手房、商办、写字楼、商铺等业务场景接口。
- 当前应用维度的结算与消耗查询。
- 面向合作方应用的鉴权、应用管理与接口调用能力。

完整的接口路径、认证与签名、请求参数、响应示例及更新内容，请以[推房开放平台接口文档](https://tuifang-open-wiki.yumeng.work/)为准。

## 申请接入

扫描二维码添加开放平台负责人微信，并在好友申请中备注：`GitHub开放平台`。

审核通过后，我们会为你开通开放平台账号。登录后可创建应用、获取 `AppKey` 与 `AppSecret`，并按已授权范围调用接口。

<img src="assets/contact-wechat.svg" alt="推房开放平台负责人微信二维码" width="300" />

## 接入流程

1. 阅读[接入前必读](https://tuifang-open-wiki.yumeng.work/)并确认所需接口。
2. 扫码添加负责人微信，备注 `GitHub开放平台`，说明团队和接入场景。
3. 审核通过后，登录[推房开放平台](https://tuifang-open.yumeng.work/open-platform/platforms)创建应用。
4. 在平台中获取密钥，按接口文档完成签名和调用。

## 技术支持

- 账号开通、业务接入：扫码添加负责人微信。
- 文档问题、可公开讨论的技术问题：提交 [Issue](../../issues/new/choose)。
- 不要在 Issue 或任何公开内容中提交 `AppSecret`、访问令牌、请求签名、客户信息或生产请求日志。

## 文档目录

- [接入前必读](https://tuifang-open-wiki.yumeng.work/)
- [租房接口](https://tuifang-open-wiki.yumeng.work/docs/open-api/rental.html)
- [二手房接口](https://tuifang-open-wiki.yumeng.work/docs/open-api/second-hand.html)
- [商办账号接口](https://tuifang-open-wiki.yumeng.work/docs/open-api/commercial-account.html)
- [写字楼接口](https://tuifang-open-wiki.yumeng.work/docs/open-api/office.html)
- [商铺接口](https://tuifang-open-wiki.yumeng.work/docs/open-api/shop.html)
- [结算与消耗接口](https://tuifang-open-wiki.yumeng.work/docs/open-api/settlement.html)

## 安全说明

密钥仅用于服务端调用。请不要将 `AppSecret` 写入前端代码、公开仓库、截图、Issue 或聊天记录。发现安全问题请按 [SECURITY.md](SECURITY.md) 的方式联系。
