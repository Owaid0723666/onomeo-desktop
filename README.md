# onomeo desktop

A Windows app for working on code with AI characters. It runs the open-source [Codex](https://github.com/openai/codex) agent in the background and uses the free models on [onomeo.com](https://onomeo.com) by default. You can also connect any other model service.

> **Public beta.** onomeo desktop is in public beta, and not every feature is guaranteed to work correctly. We are collecting as much feedback as we can: tell us what breaks or what you would like to see with the envelope button at the bottom left of the app, or through the [feedback form](https://onomeo.com/help#feedback).

## Download

Windows 10 or 11, 64-bit: download `onomeo-setup-<version>.exe` from the [latest release](https://github.com/Owaid0723666/onomeo-desktop/releases/latest).

The installer is not code-signed yet, so Windows may show "Windows protected your PC". Choose **More info**, then **Run anyway**.

After installation, the app checks this page for new versions and updates itself.

macOS and Linux versions are not available yet.

## What it does

- Characters work in the project folder you choose. Tuanzi reads, edits and runs commands; Ayan reviews the changes.
- Every file change is shown before it is applied. You can accept or reject each part separately, or roll the conversation back.
- Import SillyTavern character cards and lorebooks, or write your own characters.
- Web search, MCP tools and skills, a terminal, Git, and voice input.
- Use it from your phone or another computer on the same network.

## Licenses

onomeo desktop includes OpenAI Codex, licensed under Apache-2.0. Its license and notice are in the `licenses` folder inside the installed app. It also uses Electron, xterm.js and electron-updater, all under the MIT license.

This repository only hosts the releases.

---

## 中文说明

onomeo 桌面版：在 Windows 上让 AI 角色帮你改代码。后台运行开源的 Codex，默认使用 [onomeo.com](https://onomeo.com) 的免费模型，也可以接入其他模型服务。

**目前处于公测阶段，不保证所有功能都能正常使用。我们正在大量收集用户反馈，欢迎通过程序左下角的信封按钮或[反馈页面](https://onomeo.com/zh/help#feedback)告诉我们遇到的问题和建议。**

下载：在[最新版本](https://github.com/Owaid0723666/onomeo-desktop/releases/latest)页面下载 `onomeo-setup-版本号.exe`。安装包暂未签名，Windows 可能提示「Windows 已保护你的电脑」，请点「更多信息」，再点「仍要运行」。安装后程序会自动检查并安装新版本。
