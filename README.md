# wcbear-public

> A single-file HTML dashboard for chat analytics.
> 用于某个聊天应用的数据分析 dashboard

---

## English

### What this is

A standalone HTML file that renders a dashboard UI for analyzing chat
message statistics. Published here as a **design / code reference**.

The UI demonstrates:

- KPI overview, monthly / weekly / daily timelines (bar + candlestick)
- Top chats, top senders, message-type breakdown
- Hourly heatmap and weekday distribution
- AI-persona section (text-only mockup; backend not included)

### What this is NOT

- **Not a runnable application.** The accompanying backend (which
  produces `messages.jsonl` and serves `/api/*` endpoints) is
  intentionally not included. Opening `index.html` directly with
  `file://` or a static web server will leave most panels empty.
- **Not a tool that analyzes any specific chat platform's data.**
- **Not affiliated with any chat-platform vendor.**

### ⚠️ Legal Notice & Disclaimers

**No affiliation with any third party.** This project is an independent
work. It is **not affiliated with, endorsed by, sponsored by, or in any
way officially connected with** Tencent Holdings Limited, WeChat (微信),
or any other chat-platform vendor. All third-party trademarks, including
"WeChat" and "微信", are the property of their respective owners.

**Reference only.** Source published for study and design reference.

**No commercial use.** Forking, copying, modifying, or distributing this
code or any derivative for commercial purposes is prohibited without
written permission from the author.

**Use at your own risk.** The author accepts no liability for any direct
or indirect loss arising from the use of this code, including but not
limited to data loss, privacy violations, or legal consequences.

**Respect privacy.** Anyone who builds on top of this UI must respect
applicable privacy laws and platform terms of service in their
jurisdiction. Analyzing another person's chat history without their
explicit informed consent may violate privacy laws.

**All rights reserved.** Copyright © 2026. No license is granted other
than the right to view this source code on GitHub.

---

## 中文

### ⚠️ 法律声明与免责

**与任何第三方无关联。** 本项目为独立作品，**与腾讯控股有限公司
（Tencent Holdings Limited）、微信（WeChat）以及任何其他聊天平台
厂商均无任何隶属、授权、赞助或官方联系**。所有第三方商标，包括
但不限于「WeChat」「微信」，归各自所有人所有。

**仅供参考。** 本代码仅以学习与设计参考为目的公开。

**禁止商业使用。** 未经作者书面许可，不得 fork、复制、修改、再分发
本代码或其衍生作品用于任何商业用途。

**使用风险自负。** 作者不对因使用本代码产生的任何直接或间接损失
（包括但不限于数据丢失、隐私泄露、法律后果）承担责任。

**尊重隐私。** 任何在此基础上构建工具的人，必须遵守当地隐私法律
和相关平台用户协议。未经他人明确知情同意分析他人聊天记录可能违反
隐私法律。

**保留所有权利。** 版权所有 © 2026。除在 GitHub 上查看源代码之外，
未授予任何其他权利。

### 这是什么

一个用于分析聊天消息统计的 dashboard 。

包含以下内容：

- KPI 总览、月 / 周 / 日时间线（柱状 + K 线）
- Top 聊天对象、Top 发言者、消息类型分布
- 小时热力图、星期分布
- AI 人格模块

### 这不是什么

- **不是可独立运行的应用。** 配套后端（生成 `messages.jsonl`、提供
  `/api/*` 接口）出于法律原因刻意未包含。需要用户自行Vibe Coding补齐。直接用 `file://` 或静态服务器打开
  `index.html` 大部分面板会显示空白。
- **不是分析任何特定聊天软件数据的工具。**
- **与任何聊天平台厂商均无任何关联。**



---

## Tech stack

- Single-file HTML, no build step
- [ECharts 5.5](https://echarts.apache.org/) for charts
- [Lucide](https://lucide.dev/) icons
- Vanilla JavaScript (no framework)
