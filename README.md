# Vinez

**One AI engineering execution center. On call for your whole team.**
*一套 AI 工程能力，整个团队随时调用。*

---

## English

**Send a request in your team chat. Vinez keeps working until it’s delivered.**

<p align="center">
  <sub>Just say what needs doing. Which task, which project — its call, not yours.</sub>
  <br />
  <img src="https://vinez.ai/imgs/im-mobile-en.png" width="330" alt="A team chat thread: someone asks Vinez to look into duplicate order postings, Vinez opens task #128, reports the root cause, asks which fix to take, and delivers after a one-line answer" />
</p>

Vinez is the AI engineering execution center for teams. It turns your team’s engineering work into persistent, governed tasks and coordinates AI agents to carry them through to delivery. Every member can assign work, collaborate, and take over from chat, web, or the app — no one has to install, configure, or maintain their own agents.

### Getting started

**1. Install the server.** Pick an always-on machine your team can reach (macOS or Linux; Windows via WSL2) and run:

```bash
curl -fsSL https://vinez.ai/install.sh | sh
```

When it finishes, it prints the address of the admin console and how to sign in. Sign in to an agent CLI (Claude Code or Codex) once on this machine; it runs tasks for the whole team.

**2. Connect a chat channel.** WeCom, Feishu and Slack are supported — see [Connect a chat channel](https://vinez.ai/channels?lang=en). No public IP or domain needed. From then on, teammates just message the bot; they install nothing.

**3. Optional: install a client.** To watch the live terminal, review file changes, or take over a task yourself, use the web console or the desktop / mobile app from the [download page](https://vinez.ai/download?lang=en) (iOS: [App Store](https://apps.apple.com/app/id6806147128)).

Full walkthrough: [Getting started guide](https://vinez.ai/guide?lang=en).

<p align="center">
  <img src="https://vinez.ai/imgs/board-en.png" width="820" alt="The Vinez board: every task your team has in flight or finished, in five columns" />
</p>

**Links:**

- Website: <https://vinez.ai>
- Download & docs: <https://vinez.ai/download>
- Releases: this repository’s [Releases](https://github.com/seastart/vinez/releases)
- Feedback: this repository’s [Issues](https://github.com/seastart/vinez/issues)

This repository only distributes release artifacts (per-platform binaries and client installers); the source code is not yet public. Use is subject to the [Terms of Use](https://vinez.ai/terms).

---

## 中文

**在你们的办公 IM 里发一句需求，Vinez 持续执行到交付。**

<p align="center">
  <sub>说一句要做的事就行 —— 建哪个任务、归哪个项目，都是它自己判的</sub>
  <br />
  <img src="https://vinez.ai/imgs/im-mobile.png" width="330" alt="聊天群里的一轮往来：有人让 Vinez 查重复入账，它建了任务 #128、报出根因、停下来问该走哪种修法，得到一句回答后交付" />
</p>

Vinez 是面向团队的 AI 工程执行中枢：装在一台常开机器上的服务端（`vinezd`），把整个团队的工程需求变成持续、可治理的任务，再编排 AI agent 执行到交付。成员从聊天、Web 或 App 都能发起、协作、随时接管——不必各自安装、各自配置，也不必各自维护一套 agent。

### 安装和使用

**1. 安装服务端。** 挑一台团队都能访问的常开机器（macOS 或 Linux；Windows 经 WSL2），运行：

```bash
curl -fsSL https://vinez.ai/install.sh | sh
```

安装结束时会打印管理页面的地址与登录方式。再在这台机器上装好并登录一次 agent CLI（Claude Code 或 Codex），全团队的任务都由它执行。

**2. 接入聊天通道。** 支持企业微信、飞书、Slack，步骤见[接入聊天通道](https://vinez.ai/channels)，不需要公网 IP、不需要域名。之后同事在聊天里给机器人发消息即可，什么都不用装。

**3. 可选：安装客户端。** 想看实时终端、逐行查改动，或者亲自接管任务时，用 Web 控制台，或从[下载页](https://vinez.ai/download)安装桌面与移动客户端（iOS：[App Store](https://apps.apple.com/app/id6806147128)）。

完整说明见官网[使用指南](https://vinez.ai/guide)。

<p align="center">
  <img src="https://vinez.ai/imgs/board.png" width="820" alt="Vinez 任务看板：团队里所有正在进行和已经完成的任务，五列一屏看完" />
</p>

**链接：**

- 官网：<https://vinez.ai>
- 下载与文档：<https://vinez.ai/download>
- 版本发布：本仓库 [Releases](https://github.com/seastart/vinez/releases)
- 问题反馈：本仓库 [Issues](https://github.com/seastart/vinez/issues)

本仓库仅用于分发发布成果物（各平台二进制、客户端安装包），源代码暂未开放。使用即表示同意[使用条款](https://vinez.ai/terms)。
