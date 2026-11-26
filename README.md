<div align="center">

# Pocket Ledger · 玽记

**一个只存在你手机里的记账本。**
*A ledger that never leaves your phone.*

[中文](#中文) · [English](#english)

[**⬇ 下载最新版 / Download**](https://github.com/bendanxiaogou520/pocket-ledger/releases/latest/download/pocket-ledger.apk)

![version](https://img.shields.io/badge/version-1.48-2f6fed?style=flat-square)
![platform](https://img.shields.io/badge/Android-8.0%2B-3ddc84?style=flat-square&logo=android&logoColor=white)
![size](https://img.shields.io/badge/APK-2.6%20MB-lightgrey?style=flat-square)
![offline](https://img.shields.io/badge/offline-100%25-brightgreen?style=flat-square)

</div>

---

## 中文

### 为什么有它

市面上的记账 App 都要注册、要联网、要会员，还要把账目传到别人服务器上。

Pocket Ledger 反着来：**没有账号，没有网络权限，数据只写在手机本地**。卸载就等于全清，所以它自带导出备份。

### 功能

| 模块 | 内容 |
| --- | --- |
| **账本** | 记一笔、分类、按天/按月汇总、月度概览 |
| **待办** | 星标、截止日期、拖拽排序，和账本共用一套顶部胶囊切换 |
| **外观** | 主题皮肤（含深色）、液态玻璃导航、弹簧动效 |
| **备份** | 一键导出 JSON 到 `Documents/玽记/`，换机不丢账 |

### 界面风格

参考 Apple 的设计语言：纯黑底、超大粗体标题、横向大卡片流、底部毛玻璃胶囊 tab bar、大留白少分隔线。深色主题下是完整的液态玻璃质感。

### 怎么装

1. 点上面的 **下载最新版**（约 2.6 MB）
2. 手机提示「不允许安装未知应用」→ 这一次允许
3. 装完打开就能用

**系统要求**：Android 8.0 及以上。

> ⚠️ **卸载 App 会清空本地账目**。换机或重装前，先在 App 里导出备份。

### 隐私

- 应用**不申请网络权限**，装完可以从系统设置里验证
- 账目、待办、主题设置全部存在浏览器 `localStorage`
- 没有任何统计、埋点、崩溃上报
- 数据文件路径：`Documents/玽记/玽记_备份.json`（账本）+ `玽记_待办.json`（待办）

### 版本历史

| 版本 | 日期 | 变化 |
| --- | --- | --- |
| **v1.48** | 2026-11-24 | 版本号递增（当前） |
| v1.47 | 2026-11-12 | 液态玻璃界面、账目概览 |
| v1.42 | 2026-10-25 | 修若干记账逻辑问题 |
| v1.34 | 2026-10 | 主题皮肤系统重构 |

> 累计 49 个 `versionCode` 的迭代。

### 关于名字

原名「玽记」，取自作者网名。仓库用了通用名方便检索；**App 内部名字没改，装完后手机图标上仍显示「玽记」**。备份目录也仍叫 `Documents/玽记/`（老数据的路径不能动，动了 App 会找不到旧账）。

---

## English

### Why it exists

Every expense app on the market wants you to register, go online, buy a subscription, and hand your ledger over to someone else's server.

Pocket Ledger does the opposite: **no account, no network permission, data written only to local storage**. Uninstalling wipes everything, so it ships with a one-tap JSON export.

### Features

| Module | Contents |
| --- | --- |
| **Ledger** | Add entries, categories, daily/monthly totals, monthly overview |
| **To-dos** | Star, due dates, drag to reorder — shares the same top capsule switcher |
| **Appearance** | Theme skins (including dark), liquid-glass navigation, spring animations |
| **Backup** | One-tap JSON export to `Documents/玽记/`, survives a device change |

### Design

Borrows Apple's language: pure-black base, oversized bold titles, horizontal card flow, frosted-glass capsule tab bar, generous whitespace and few dividers. The dark theme is full liquid glass.

### Install

1. Tap **Download latest** above (~2.6 MB)
2. Allow unknown apps once when prompted
3. Open and use

**Requirements**: Android 8.0+.

> ⚠️ **Uninstalling wipes your local ledger.** Export a backup before switching or reinstalling.

### Privacy

- The app requests **no network permission** — verifiable in system settings after install
- Ledger, to-dos and theme settings all live in browser `localStorage`
- No analytics, no tracking, no crash reporting
- Backup paths: `Documents/玽记/玽记_备份.json` (ledger) and `玽记_待办.json` (to-dos)

### Version history

| Version | Date | Changes |
| --- | --- | --- |
| **v1.48** | 2026-11-24 | Version bump (current) |
| v1.47 | 2026-11-12 | Liquid-glass UI, ledger overview |
| v1.42 | 2026-10-25 | Ledger logic fixes |

49 `versionCode` iterations in total.

<sub>Formerly 玽记. The repo uses a generic name; the app's own name is unchanged. The backup directory also remains `Documents/玽记/` — moving it would orphan existing data.</sub>

---

## License

MIT — see [LICENSE](LICENSE).
