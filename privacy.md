---
title: Screeps Overmind 隐私政策 / Privacy Policy
---

# Screeps Overmind 隐私政策

生效日期：2026-11-11

Screeps Overmind（以下简称“本 App”）是 Screeps World 的非官方第三方客户端，由个人开发者维护。本政策说明本 App 如何处理你的信息。

## 我们不收集你的数据

- 本 App 没有开发者自建的服务器、账号系统、统计分析、广告或第三方 SDK，不追踪你，也不把任何数据发送给开发者。
- 本 App 只和你在连接设置中填写的游戏服务器通信（默认是 Screeps, LLC 运营的官方服务器 `screeps.com`）。你向该服务器发送和从该服务器获取的内容，适用该服务器运营方的条款与隐私政策。

## 保存在你设备上的信息

| 信息 | 存储位置 | 用途 |
| --- | --- | --- |
| Auth Token、服务器密码 | iOS 钥匙串，仅限本设备，不随 iCloud 同步 | 向你配置的游戏服务器验证身份 |
| 服务器地址、端口、路径前缀、WebSocket 地址、备注、账号名 | 本 App 的本地设置 | 保存与切换连接 |
| 游戏接口响应缓存 | 系统缓存目录，按服务器与 Token 隔离 | 打开页面时先显示上次数据 |
| 请求日志（路径、状态、耗时、错误） | 仅内存，最多 500 条，不含 Token 和请求体，退出 App 即清除 | 排查连接与限流问题 |

## 删除你的信息

- 在 App 内删除某个连接，会同时删除该连接在钥匙串中的 Token 和服务器密码。
- 系统可能在 App 卸载后仍保留钥匙串条目，建议卸载前先在 App 内删除连接。你也可以随时在 Screeps 网站的账号设置中吊销 Token。
- 缓存可由系统自动清理，卸载 App 时一并删除。

## 儿童

本 App 不面向 13 岁以下儿童，也不会有意收集任何人的个人信息。

## 政策变更

政策如有变更，会更新本页面并修改生效日期。

## 联系方式

clarkleix@gmail.com

---

# Screeps Overmind Privacy Policy

Effective date: November 11, 2026

Screeps Overmind ("the App") is an unofficial third-party client for Screeps World, maintained by an independent developer.

**We do not collect your data.** The App has no developer-operated servers, accounts, analytics, advertising, tracking, or third-party SDKs, and it never sends any data to the developer. The App only talks to the game server you configure (by default the official server `screeps.com`, operated by Screeps, LLC). Content you exchange with that server is governed by its operator's terms and privacy policy.

**Data stored on your device:**

- Auth tokens and server passwords are stored in the iOS Keychain, limited to this device and not synced via iCloud.
- Server addresses, ports, path prefixes, WebSocket addresses, notes, and account names are stored in the App's local settings.
- Game API responses are cached in the system Caches directory, kept separate for each server and token.
- Request logs (path, status, duration, error; never tokens or request bodies) are kept in memory only, up to 500 entries, and are cleared when the App quits.

**Deleting your data:** Deleting a connection in the App removes its token and password from the Keychain. iOS may keep Keychain items after the App is uninstalled, so delete your connections first. You can revoke tokens at any time in your Screeps account settings.

**Children:** The App is not directed to children under 13.

**Changes:** Any update to this policy will be posted on this page with a new effective date.

**Contact:** clarkleix@gmail.com
