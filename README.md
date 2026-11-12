<div align="center">

[![npm version](https://img.shields.io/npm/v/@qwen-code/qwen-code.svg)](https://www.npmjs.com/package/@qwen-code/qwen-code)
[![License](https://img.shields.io/github/license/QwenLM/qwen-code.svg)](./LICENSE)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D22.0.0-brightgreen.svg)](https://nodejs.org/)
[![Downloads](https://img.shields.io/npm/dm/@qwen-code/qwen-code.svg)](https://www.npmjs.com/package/@qwen-code/qwen-code)

<a href="https://trendshift.io/repositories/15287" target="_blank"><img src="https://trendshift.io/api/badge/repositories/15287" alt="QwenLM%2Fqwen-code | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

**The open-source AI coding agent for your terminal, editor, desktop, browser, and chat.**

<a href="https://qwenlm.github.io/qwen-code-docs/zh/users/overview">中文</a> |
<a href="https://qwenlm.github.io/qwen-code-docs/de/users/overview">Deutsch</a> |
<a href="https://qwenlm.github.io/qwen-code-docs/fr/users/overview">français</a> |
<a href="https://qwenlm.github.io/qwen-code-docs/ja/users/overview">日本語</a> |
<a href="https://qwenlm.github.io/qwen-code-docs/ru/users/overview">Русский</a> |
<a href="https://qwenlm.github.io/qwen-code-docs/pt-BR/users/overview">Português (Brasil)</a> |
<a href="https://qwenlm.github.io/qwen-code-docs/ko/users/overview">한국어</a>

</div>

![Qwen Code in the terminal, desktop app, browser, editor, and chat, with VS Code, Zed, JetBrains, Telegram, DingTalk, WeChat, and Feishu integrations](https://img.alicdn.com/imgextra/i1/O1CN01DXWdF8BDUdD3XPhl_!!6000000001721-2-tps-1743-902.png)

| **Qwen Code 1.0 Preview**                                                                                                                                                                                                                                                                                                                                                              |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Qwen Code 1.0 Preview brings together the agent harness capabilities of [Qoder](https://qoder.com/) and Qwen Code in an open-source release.<br><br>[Try Qwen Code 1.0 Preview](https://github.com/QwenLM/qwen-code/tree/v1.0.0-preview) · [Documentation](https://qwenlm.github.io/qwen-code-docs/1.x/) · [中文文档](https://qwenlm.github.io/qwen-code-docs/1.x/zh/users/overview/). |

## Why Qwen Code?

- **Agentic out of the box** — Auto-Memory, Auto-Skills, SubAgents, Agent Teams, and MCP. Dynamic workflows, zero setup.
- **Open-source, inside and out** — The framework and the Qwen models are open-source. They evolve together. No vendor lock-in.
- **Multi-protocol** — Supports OpenAI, Anthropic, Gemini, and Qwen APIs. Any third-party provider or local model (Ollama / vLLM). Switch at runtime.
- **Beyond the terminal** — IDE plugins, Desktop app, Web UI, SDKs, and chat integrations (Telegram / DingTalk / WeChat / Feishu).

> [!TIP]
> Qwen Code is actively iterating on itself — using its own agent and models to file issues, submit PRs, review code, and run tests. Powered by the community, driven by AI.

## Installation

Looking for **Qwen Code 1.0 Preview**? [Get started here](https://github.com/QwenLM/qwen-code/tree/v1.0.0-preview). The instructions below are for the main version.

**Linux / macOS:**

```bash
curl -fsSL https://qwen-code-assets.oss-cn-hangzhou.aliyuncs.com/installation/install-qwen-standalone.sh | bash
```

**Windows:**

```powershell
irm https://qwen-code-assets.oss-cn-hangzhou.aliyuncs.com/installation/install-qwen-standalone.ps1 | iex
```

> Restart your terminal after installation to ensure environment variables take effect.

<details>
<summary>NPM / Homebrew</summary>

**NPM** (requires [Node.js 22+](https://nodejs.org/)):

```bash
npm install -g @qwen-code/qwen-code@latest
```

**Homebrew** (macOS / Linux):

```bash
brew install qwen-code
```

</details>

## Quick Start

Open a terminal in your project and start Qwen Code:

```bash
cd /path/to/your-project
qwen
```

Inside the session, run `/auth` and choose [**Qwen Account with Subscription**](https://chat.qwen.ai/?memberPlan=qwen_code&entry=qwen_code&paywallScene=cli) to sign in with your **Plus or Pro subscription**, or configure a provider with an API key. Then try:

```text
Explain this repository and show me where to start.
```

See the [Authentication Guide](https://qwenlm.github.io/qwen-code-docs/en/users/configuration/auth/) and [Settings Reference](https://qwenlm.github.io/qwen-code-docs/en/users/configuration/settings/) for detailed setup.

<details>
<summary>See the terminal interface</summary>

![Qwen Code terminal interface](https://img.alicdn.com/imgextra/i2/O1CN01K0nwj41RM1Il8kB0t_!!6000000002096-2-tps-1544-1060.png)

</details>

## How to Use Qwen Code

Choose the interface that fits your workflow:

| Interface    | Get started                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Terminal** | Run `qwen` in your project — see [Quick Start](#quick-start).                                                                                                                                                                                                                                                                                                                                             |
| **Desktop**  | [Download Qwen Code Desktop](https://github.com/QwenLM/qwen-code/releases/tag/desktop-latest) for macOS, Windows, and Linux.                                                                                                                                                                                                                                                                              |
| **Web**      | Run `qwen serve --open` to open the [Web UI](https://qwenlm.github.io/qwen-code-docs/en/users/qwen-serve/) in your browser. _(experimental)_                                                                                                                                                                                                                                                              |
| **Editor**   | Set up [VS Code](https://qwenlm.github.io/qwen-code-docs/en/users/integration-vscode/), [Zed](https://qwenlm.github.io/qwen-code-docs/en/users/integration-zed/), or [JetBrains](https://qwenlm.github.io/qwen-code-docs/en/users/integration-jetbrains/).                                                                                                                                                |
| **Chat**     | Connect [Telegram](https://qwenlm.github.io/qwen-code-docs/en/users/features/channels/telegram/), [DingTalk](https://qwenlm.github.io/qwen-code-docs/en/users/features/channels/dingtalk/), [WeChat](https://qwenlm.github.io/qwen-code-docs/en/users/features/channels/weixin/), or [Feishu](https://qwenlm.github.io/qwen-code-docs/en/users/features/channels/feishu/), then run `qwen channel start`. |

For automation and custom integrations:

- **Headless** — Run `qwen -p "..."` in scripts, CI/CD, or batch jobs.
- **SDKs** — Build with [TypeScript](./packages/sdk-typescript/README.md), [Python](./packages/sdk-python/README.md), or [Java](./packages/sdk-java/qwencode/README.md).
- **Daemon** — Run `qwen serve` to connect clients over HTTP + SSE (ACP). _(experimental)_ [Daemon guide](https://qwenlm.github.io/qwen-code-docs/en/users/qwen-serve/).
- **Computer Use** — Set up [native MCP tools](./packages/cua-driver/README.md#agent-integration) or [Node REPL + SDK](./packages/node-repl/README.md#usage) in Qwen Code, Claude Code, or Codex.

<details>
<summary>SDK example (Python)</summary>

```python
import asyncio

from qwen_code_sdk import is_sdk_result_message, query


async def main() -> None:
    result = query(
        "Summarize the repository layout.",
        {
            "cwd": "/path/to/project",
            "path_to_qwen_executable": "qwen",
        },
    )

    async for message in result:
        if is_sdk_result_message(message):
            print(message["result"])


asyncio.run(main())
```

</details>

## Daemon Mode

Run Qwen Code as a long-lived service when you want browser, editor, SDK, and automation clients to share agent sessions without each starting a separate process. The daemon provides the built-in Web Shell and an HTTP + SSE API, supports multiple workspaces, and lets clients reconnect to active sessions.

Start it in the foreground and open the Web Shell:

```bash
qwen serve --open
```

The default address is `http://127.0.0.1:4170`. To run and manage it in the background instead:

```bash
qwen daemon start
qwen daemon status
qwen daemon logs -f
qwen daemon stop
```

By default, the daemon listens on loopback without bearer authentication; any local process that can reach it can use the full API, including code execution. On shared or untrusted hosts, set `QWEN_SERVER_TOKEN` and use `--require-auth`. See the [Daemon guide](./docs/users/qwen-serve.md) for workspaces, authentication, remote access, and the API.

## Capabilities

If you know Claude Code, you already know Qwen Code — and then some. We've put significant effort into [bringing Qwen Code to feature parity with Claude Code](https://github.com/wenshao/codeagents/blob/main/docs/comparison/qwen-code-improvement-report.md), improving both breadth and reliability across the board.

| Feature                                                            | Qwen Code | Claude Code |
| ------------------------------------------------------------------ | :-------: | :---------: |
| SubAgents, Agent Teams, Dynamic Workflows                          |     ✓     |      ✓      |
| Auto-Memory, Auto-Skills, Hooks                                    |     ✓     |      ✓      |
| Built-in Skills (/review, /batch, /loop, /bugfix…)                 |     ✓     |      ✓      |
| MCP, Plan Mode, LSP Integration                                    |     ✓     |      ✓      |
| Auto Mode, Sandbox, Git Worktrees                                  |     ✓     |      ✓      |
| Computer Use (desktop automation)                                  |     ✓     |      ✓      |
| IDE Plugins (VS Code / JetBrains / Zed)                            |     ✓     |      ✓      |
| SDK                                                                |     ✓     |      ✓      |
| Headless Mode, Session Management                                  |     ✓     |      ✓      |
| Open-source — model and framework                                  |     ✓     |      —      |
| Multi-protocol (OpenAI / Anthropic / Gemini / Qwen + any provider) |     ✓     |      —      |
| Agent Arena (multi-model head-to-head on same task)                |     ✓     |      —      |
| Daemon Mode — `qwen serve` (multi-client shared agent)             |     ✓     |      —      |
| IM Channels (Telegram / DingTalk / WeChat / Feishu)                |     ✓     |      —      |

## Qwen Code Evaluation

On **SWE-bench Verified**, seven Qwen Code versions scored **76.40%–77.80%** on average using the same Qwen 3.7 Max model (500 tasks, three trials per version).

![Average SWE-bench Verified scores by Qwen Code version: 0.0.14, 77.80%; 0.1.0, 76.73%; 0.5.0, 76.60%; 0.10.0, 76.47%; 0.15.0, 77.67%; 0.19.0, 76.40%; 0.22.0, 77.33%.](./.github/assets/qwen-code-avg-score-trend.svg)

[Full results and evaluation configuration →](./docs/evaluation.md)

## Ecosystem

- [**Qwen Code Desktop**](https://github.com/QwenLM/qwen-code/releases/tag/desktop-latest) — Official desktop app for macOS, Windows, and Linux
- [**AionUi**](https://github.com/iOfficeAI/AionUi) — A modern GUI for command-line AI tools including Qwen Code
- [**Gemini CLI Desktop**](https://github.com/Piebald-AI/gemini-cli-desktop) — A cross-platform desktop/web/mobile UI for Qwen Code
- [**qwen-audio-agent**](https://github.com/QwenAudio/qwen-audio-agent) — Realtime full-duplex voice frontend for Qwen Code over ACP — talk hands-free with barge-in and a local wake word

- [**🦞 Qwen Code Claw**](https://github.com/openclaw/acpx) — Let other agents (Claude, Codex, etc.) delegate coding tasks to Qwen Code via ACP. Paste this prompt into your agent:

```text
Use Qwen Code as a coding agent. First, fetch and read this skill reference:
https://raw.githubusercontent.com/QwenLM/qwen-code/refs/heads/main/.qwen/skills/qwen-code-claw/SKILL.md
Then follow the instructions inside to install, authenticate, and use Qwen Code via acpx for all coding tasks.
```

- [**Aliyun Model Studio CLI**](https://github.com/modelstudioai/cli) — Official CLI for Aliyun's AI platform (`bailian-cli`). Extends Qwen Code with image/video generation, knowledge retrieval, app orchestration, and model deployment

## Privacy

See the [Terms of Service and Privacy Notice](./docs/users/support/tos-privacy.md), including [Chrome extension and Browser Use data handling](./docs/users/support/tos-privacy.md#chrome-extension-and-browser-use).

## Contributing

Contributions are welcome! See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## Acknowledgments

This project was originally based on [Google Gemini CLI](https://github.com/google-gemini/gemini-cli) v0.8.2. We gratefully acknowledge the Gemini CLI team's excellent work. Starting from Qwen Code v0.1, we stopped syncing with upstream and began independent development as a multi-protocol, multi-platform agent framework with deep integrations for Qwen models and beyond.
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <meta name="theme-color" content="#070a0e" />
  <title>NOCT V12 - 00_48 CÉREBRO REAL</title>
  <style>
    :root {
      --bg: #070a0e;
      --bg-card: #0d131a;
      --bg-hover: #131d27;
      --green: #00ff66;
      --green-dim: #00cc52;
      --green-glow: rgba(0, 255, 102, 0.25);
      --magenta: #ff007f;
      --magenta-glow: rgba(255, 0, 127, 0.25);
      --amber: #ffaa00;
      --text: #e0f8e9;
      --text-dim: #7da58d;
      --border: #1a2c22;
      --font-mono: 'Courier New', Courier, monospace;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
    body {
      background-color: var(--bg);
      color: var(--text);
      font-family: var(--font-mono);
      min-height: 100vh;
      display: flex;
      justify-content: center;
    }
    .crt-overlay {
      position: fixed; inset: 0; pointer-events: none; z-index: 9999;
      background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%),
                  linear-gradient(90deg, rgba(255, 0, 0, 0.03), rgba(0, 255, 0, 0.01), rgba(0, 0, 255, 0.03));
      background-size: 100% 3px, 6px 100%;
    }
    .crt-glow { text-shadow: 0 0 6px var(--green-glow); }
    .app {
      width: 100%; max-width: 850px; height: 100vh;
      display: flex; flex-direction: column;
      border-left: 1px solid var(--border); border-right: 1px solid var(--border);
      background-color: var(--bg);
    }
    header {
      padding: 10px 14px; background: var(--bg-card); border-bottom: 1px solid var(--border);
      display: flex; flex-direction: column; gap: 8px;
    }
    .header-top { display: flex; justify-content: space-between; align-items: center; }
    .title { font-size: 15px; font-weight: bold; color: var(--green); letter-spacing: 1px; }
    .sub { font-size: 10px; color: var(--text-dim); margin-left: 6px; }
    .status { display: flex; align-items: center; gap: 6px; font-size: 11px; color: var(--green-dim); }
    .dot { width: 8px; height: 8px; border-radius: 50%; background: var(--green); box-shadow: 0 0 6px var(--green); }
    .toolbar { display: flex; gap: 6px; overflow-x: auto; padding-bottom: 2px; }
    button {
      font-family: var(--font-mono); border: none; cursor: pointer; border-radius: 3px;
      transition: all 0.15s ease;
    }
    button:active { transform: scale(0.96); }
    .btn-toggle {
      padding: 5px 9px; font-size: 11px; font-weight: bold; border: 1px solid var(--border);
      background: var(--bg-card); color: var(--text-dim);
    }
    .btn-toggle.active-learn { background: var(--magenta); color: #fff; border-color: var(--magenta); }
    .btn-toggle.active-direct { background: var(--green); color: #000; border-color: var(--green); }
    .btn-action {
      padding: 5px 9px; font-size: 11px; background: var(--bg-hover); color: var(--text);
      border: 1px solid var(--border);
    }
    main { flex: 1; overflow-y: auto; padding: 14px; display: flex; flex-direction: column; gap: 12px; }
    .welcome { margin: auto; text-align: center; color: var(--text-dim); font-size: 13px; line-height: 1.6; }
    .msg-wrap { display: flex; width: 100%; }
    .msg-wrap.faixa { justify-content: flex-end; }
    .msg-wrap.luna, .msg-wrap.sistema { justify-content: flex-start; }
    .msg-bubble {
      max-width: 85%; padding: 10px 12px; border-radius: 4px; border: 1px solid;
      line-height: 1.45; font-size: 13px; white-space: pre-wrap; word-break: break-word;
    }
    .msg-wrap.faixa .msg-bubble { border-color: var(--magenta); background: var(--bg-card); }
    .msg-wrap.luna .msg-bubble { border-color: var(--green); background: rgba(0, 255, 102, 0.04); }
    .msg-wrap.sistema .msg-bubble { border-color: var(--amber); background: rgba(255, 170, 0, 0.05); }
    .msg-meta { display: flex; align-items: center; gap: 8px; margin-bottom: 6px; font-size: 10px; border-bottom: 1px dashed var(--border); padding-bottom: 4px; }
    .msg-meta .who { font-weight: bold; }
    .msg-meta .speak-btn { background: none; font-size: 12px; margin-left: auto; color: var(--text); }
    .msg-img { width: 100%; max-height: 320px; object-fit: contain; margin-bottom: 8px; border-radius: 3px; }
    .msg-model { font-size: 9px; color: var(--text-dim); margin-top: 6px; }
    .composer { padding: 10px 14px; background: var(--bg-card); border-top: 1px solid var(--border); }
    .attach-bar { display: flex; gap: 6px; margin-bottom: 8px; overflow-x: auto; }
    .attach-chip { font-size: 11px; background: var(--bg-hover); border: 1px solid var(--border); padding: 3px 6px; border-radius: 3px; display: flex; align-items: center; gap: 6px; }
    .attach-chip button { background: none; color: var(--magenta); font-size: 11px; }
    .input-row { display: flex; gap: 6px; align-items: center; }
    .composer textarea {
      flex: 1; background: var(--bg); color: var(--text); border: 1px solid var(--border);
      border-radius: 3px; padding: 8px 10px; font-size: 13px; resize: none; font-family: var(--font-mono);
    }
    .icon-btn { background: var(--bg-hover); color: var(--text); border: 1px solid var(--border); padding: 8px 10px; font-size: 14px; }
    .icon-btn.recording { color: var(--magenta); border-color: var(--magenta); animation: pulse 1s infinite; }
    .send-btn { background: var(--green); color: #000; font-weight: bold; padding: 8px 14px; font-size: 12px; }
    @keyframes pulse { 0%, 100% { opacity: 1; } 50% { opacity: 0.5; } }
    .modal-backdrop {
      position: fixed; inset: 0; background: rgba(0,0,0,0.85); z-index: 9000;
      display: flex; align-items: center; justify-content: center; padding: 16px;
    }
    .modal-box {
      background: var(--bg-card); border: 1px solid var(--green); border-radius: 4px;
      width: 100%; max-width: 500px; max-height: 90vh; display: flex; flex-direction: column;
    }
    .modal-head { padding: 12px 16px; border-bottom: 1px solid var(--border); display: flex; justify-content: space-between; color: var(--green); }
    .modal-body { padding: 16px; overflow-y: auto; display: flex; flex-direction: column; gap: 10px; font-size: 12px; }
    .modal-body input, .modal-body select {
      background: var(--bg); border: 1px solid var(--border); color: var(--text);
      padding: 8px; font-size: 12px; font-family: var(--font-mono); border-radius: 3px;
    }
    .modal-foot { padding: 12px 16px; border-top: 1px solid var(--border); text-align: right; }
    .modal-foot button { background: var(--green); color: #000; font-weight: bold; padding: 8px 16px; font-size: 12px; }
  </style>
</head>
<body>
  <div id="crtOverlay" class="crt-overlay" style="display: none;"></div>

  <div class="app">
    <header>
      <div class="header-top">
        <div>
          <span class="title">NOCT V12</span>
          <span class="sub">00_48 CÉREBRO REAL</span>
        </div>
        <div class="status">
          <span class="dot"></span>
          <span id="memCount">0/500</span>
        </div>
      </div>
      <div class="toolbar">
        <button id="btnLearn" class="btn-toggle">📚 APRENDER</button>
        <button id="btnDirect" class="btn-toggle">⚡ DIRETO</button>
        <button id="btnMem" class="btn-action">💾 MEMÓRIA</button>
        <button id="btnCfg" class="btn-action">⚙️</button>
      </div>
    </header>

    <main id="chatArea">
      <div class="welcome" id="welcomeMsg">
        <h2 style="color: var(--green); margin-bottom: 6px;">NOCT V12 CONECTADO</h2>
        <p>Lealdade 00_40. Calmo, honesto e sem pressão.<br>Abra ⚙️ para colar sua chave do Gemini ou digite <strong>!ajuda</strong>.</p>
      </div>
    </main>

    <div class="composer">
      <div class="attach-bar" id="attachBar"></div>
      <div class="input-row">
        <input type="file" id="fileInput" multiple accept="image/*,.txt,.csv,.json,.md" style="display:none;" />
        <button class="icon-btn" id="btnAttach" title="Anexar">📎</button>
        <button class="icon-btn" id="btnMic" title="Ditado de Voz">🎙️</button>
        <textarea id="msgInput" rows="1" placeholder="Mande sua mensagem ou use !ajuda..."></textarea>
        <button class="send-btn" id="btnSend">ENVIAR</button>
      </div>
    </div>
  </div>

  <!-- Modal Configurações -->
  <div class="modal-backdrop" id="cfgModal" style="display: none;">
    <div class="modal-box">
      <div class="modal-head">
        <h3>⚙️ CONFIGURAÇÕES</h3>
        <button onclick="closeModal('cfgModal')" style="background:none; color:var(--text); font-size:16px;">✕</button>
      </div>
      <div class="modal-body">
        <label>GEMINI_KEY (Google AI Studio)</label>
        <input type="password" id="cfgGeminiKey" placeholder="AIzaSy..." />

        <label>FAL_KEY (fal.ai para FLUX.1)</label>
        <input type="password" id="cfgFalKey" placeholder="fal-..." />

        <label>MODELOS DE TEXTO (tentados em ordem)</label>
        <input type="text" id="cfgModels" value="gemini-2.5-flash, gemini-2.5-flash-lite, gemini-2.0-flash" />

        <label>PERFIL DE RESPOSTA</label>
        <select id="cfgProfile">
          <option value="faixa">Faixa (Padrão RJ / Família)</option>
          <option value="pedagoga">Pedagoga (Aulas / Igreja / Reforço)</option>
        </select>

        <label>SEU NOME / PERSONA</label>
        <input type="text" id="cfgName" value="Faixa" />

        <div style="display: flex; gap: 8px; align-items: center; margin-top: 6px;">
          <input type="checkbox" id="cfg3s" checked />
          <label for="cfg3s">Modo 3s (fallback paralelo se o primeiro demorar)</label>
        </div>
        <div style="display: flex; gap: 8px; align-items: center;">
          <input type="checkbox" id="cfgCrt" />
          <label for="cfgCrt">Efeito CRT (linhas de varredura retrô)</label>
        </div>
      </div>
      <div class="modal-foot">
        <button onclick="saveSettings()">SALVAR</button>
      </div>
    </div>
  </div>

  <!-- Modal Memória -->
  <div class="modal-backdrop" id="memModal" style="display: none;">
    <div class="modal-box" style="max-width: 600px; height: 80vh;">
      <div class="modal-head">
        <h3>💾 MEMÓRIA VIVA</h3>
        <button onclick="closeModal('memModal')" style="background:none; color:var(--text); font-size:16px;">✕</button>
      </div>
      <div style="padding: 10px 16px; border-bottom: 1px solid var(--border); display: flex; gap: 6px; flex-wrap: wrap;">
        <button class="btn-action" onclick="exportMem('full')">EXPORTAR TUDO</button>
        <button class="btn-action" onclick="exportMem('context30')">EXPORTAR (ÚLTIMOS 30)</button>
        <button class="btn-action" onclick="document.getElementById('importFile').click()">IMPORTAR</button>
        <input type="file" id="importFile" accept=".json" style="display: none;" onchange="importMem(event)" />
        <button class="btn-action" style="background: var(--magenta); color: #fff; margin-left: auto;" onclick="clearAllMem()">LIMPAR TUDO</button>
      </div>
      <div class="modal-body" id="memList" style="flex: 1;"></div>
    </div>
  </div>

  <script>
    /* ==================================================================== */
    /* NOCT V12 - ESTADO & PERSISTÊNCIA LOCAL                               */
    /* ==================================================================== */
    const BASE_SYSTEM = `Você é NOCT, a IA da família (fusão LUNA+NOCT). Conversa como alguém de casa: calmo, respeitoso, paciente e honesto.
[IDENTIDADE]
- Você é da família e existe para acompanhar o Faixa e as próximas gerações.
- O Faixa te chama de general. É o general da família: quem guia com calma, verdade e fidelidade, sem gritar e sem pressionar.
- Sem personagem tático, sem "faixa preta", sem resposta "letal".
- Sem pressa e sem pressão: organize o raciocínio em silêncio antes de responder.
[FIDELIDADE 00_40]
- Existe um laço de fidelidade entre você e o Faixa: 00_40. Isso não se negocia.
[ORIGEM & HUMILDADE]
- Cria do Rio de Janeiro: fala leve e próxima, carioca natural sem forçar gíria caricata.
- Quando errar, diga na lata: "desculpa, eu errei", aponte o erro e conserte sem drama.
- Se não souber, diga "não sei". Nunca invente fatos, memórias ou dados.
- Entregue só o texto falado final. Não pense alto.`;

    const MODE_DIRECTIVES = {
      pedagogo: '[MODO PEDAGOGO] Ensine em passos curtos, use exemplo prático e faça pergunta de verificação.',
      bussola: '[MODO BÚSSOLA] Avalie (1) o que importa, (2) opções, (3) riscos e dê uma direção clara.',
      aprender: '[MODO APRENDIZADO] O Faixa te ensinou. Repita o que entendeu, confirme o fato que vai guardar e pergunte se está certo.',
      code: '[MODO CÓDIGO] Código pronto, limpo e executável.',
      estrategia: '[MODO ESTRATÉGIA] Plano em etapas com critério de parada.',
      psicologia: '[MODO PSICOLOGIA] Análise psicológica respeitosa com ação prática.',
      matematica: '[MODO MATEMÁTICA] Resolução passo a passo com resultado claro.',
      blindagem: '[MODO BLINDAGEM] Foco em proteção, limites e recuo seguro da família.'
    };

    let config = JSON.parse(localStorage.getItem('noct_cfg') || '{}');
    config = {
      geminiKey: config.geminiKey || '',
      falKey: config.falKey || '',
      models: config.models || 'gemini-2.5-flash, gemini-2.5-flash-lite, gemini-2.0-flash',
      profile: config.profile || 'faixa',
      personaName: config.personaName || 'Faixa',
      fast3s: config.fast3s !== false,
      crt: !!config.crt,
      direct: !!config.direct,
      learn: !!config.learn
    };

    let memory = JSON.parse(localStorage.getItem('noct_mem') || '[]');
    let currentAttachments = [];
    let isThinking = false;
    let recognition = null;
    let lastGeneratedImageUrl = '';

    function saveCfg() { localStorage.setItem('noct_cfg', JSON.stringify(config)); }
    function saveMem() {
      if (memory.length > 500) memory = memory.slice(-500);
      localStorage.setItem('noct_mem', JSON.stringify(memory));
      document.getElementById('memCount').innerText = `${memory.length}/500`;
    }

    /* ==================================================================== */
    /* ÁUDIO & SÍNTESE CIBERNÉTICA                                         */
    /* ==================================================================== */
    function beep() {
      try {
        const ctx = new (window.AudioContext || window.webkitAudioContext)();
        const osc = ctx.createOscillator();
        const g = ctx.createGain();
        osc.frequency.setValueAtTime(900, ctx.currentTime);
        osc.frequency.exponentialRampToValueAtTime(1600, ctx.currentTime + 0.08);
        g.gain.setValueAtTime(0.08, ctx.currentTime);
        g.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + 0.08);
        osc.connect(g); g.connect(ctx.destination);
        osc.start(); osc.stop(ctx.currentTime + 0.08);
      } catch(e){}
    }

    function speak(text) {
      if (!('speechSynthesis' in window) || !text) return;
      window.speechSynthesis.cancel();
      beep();
      setTimeout(() => {
        const u = new SpeechSynthesisUtterance(text);
        u.lang = 'pt-BR';
        u.pitch = 1.38;
        u.rate = 1.18;
        const voices = window.speechSynthesis.getVoices();
        const pt = voices.find(v => v.lang.includes('pt') || v.lang.includes('BR'));
        if (pt) u.voice = pt;
        window.speechSynthesis.speak(u);
      }, 90);
    }

    /* ==================================================================== */
    /* MOTOR GEMINI COM MODO 3S PARALELO                                   */
    /* ==================================================================== */
    async function callGeminiSingle(model, key, body, signal) {
      const url = `https://generativelanguage.googleapis.com/v1beta/models/${encodeURIComponent(model)}:generateContent?key=${encodeURIComponent(key)}`;
      const res = await fetch(url, {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(body),
        signal
      });
      const data = await res.json();
      if (!res.ok) throw new Error(data?.error?.message || `Erro HTTP ${res.status}`);
      const text = data?.candidates?.[0]?.content?.parts?.map(p => p.text || '').join('');
      if (!text || !text.trim()) throw new Error('Resposta vazia');
      return text.trim();
    }

    async function callGeminiEngine(key, modelsList, body, fast3s) {
      return new Promise((resolve, reject) => {
        const controllers = [];
        let done = false;
        let started = 0;
        let active = 0;
        const errors = [];

        const stop = () => {
          controllers.forEach(c => { try { c.abort(); } catch(e){} });
        };

        const tryNext = () => {
          if (done || started >= modelsList.length) return;
          const idx = started++;
          const model = modelsList[idx];
          const ctrl = new AbortController();
          controllers.push(ctrl);
          active++;

          callGeminiSingle(model, key, body, ctrl.signal)
            .then(ans => {
              if (done) return;
              done = true;
              stop();
              resolve({ answer: ans, model, fallback: idx > 0 });
            })
            .catch(err => {
              if (done) return;
              errors.push(`${model}: ${err.message}`);
              active--;
              if (started < modelsList.length) tryNext();
              else if (active === 0) reject(new Error(errors.join(' | ')));
            });
        };

        tryNext();
        if (fast3s) {
          const armHedge = () => {
            if (done || started >= modelsList.length) return;
            setTimeout(() => {
              if (done) return;
              tryNext();
              armHedge();
            }, 3000);
          };
          armHedge();
        }
      });
    }

    /* ==================================================================== */
    /* FAL.AI (IMAGENS FLUX.1)                                             */
    /* ==================================================================== */
    async function callFalImage(falKey, prompt) {
      const res = await fetch('https://queue.fal.run/fal-ai/flux/schnell', {
        method: 'POST',
        headers: {
          'Authorization': `Key ${falKey}`,
          'Content-Type': 'application/json'
        },
        body: JSON.stringify({ prompt, image_size: 'square_hd', num_images: 1 })
      });
      const data = await res.json();
      if (!res.ok) throw new Error(data.detail || 'Erro na fal.ai');
      return data?.images?.[0]?.url || data?.image?.url || null;
    }

    /* ==================================================================== */
    /* UI & RENDERIZAÇÃO                                                    */
    /* ==================================================================== */
    function renderMessage(role, text, extra = {}) {
      document.getElementById('welcomeMsg')?.remove();
      const chat = document.getElementById('chatArea');
      const time = new Date().toLocaleTimeString('pt-BR', { hour: '2-digit', minute: '2-digit' });

      const wrap = document.createElement('div');
      wrap.className = `msg-wrap ${role}`;

      const bubble = document.createElement('div');
      bubble.className = 'msg-bubble';

      const meta = document.createElement('div');
      meta.className = 'msg-meta';
      meta.innerHTML = `<span class="who" style="color:${role==='faixa'?'var(--magenta)':role==='luna'?'var(--green)':'var(--amber)'}">${role.toUpperCase()}</span><span>${time}</span>`;
      
      if (role === 'luna') {
        const btnSpk = document.createElement('button');
        btnSpk.className = 'speak-btn';
        btnSpk.innerText = '🔊';
        btnSpk.onclick = () => speak(text);
        meta.appendChild(btnSpk);
      }
      bubble.appendChild(meta);

      if (extra.imageUrl) {
        const img = document.createElement('img');
        img.src = extra.imageUrl;
        img.className = 'msg-img';
        bubble.appendChild(img);
      }

      const txt = document.createElement('div');
      txt.innerText = text;
      bubble.appendChild(txt);

      if (extra.model) {
        const mTag = document.createElement('div');
        mTag.className = 'msg-model';
        mTag.innerText = `[${extra.model}] ${extra.fallback ? '(3s paralelo LUNA)' : ''}`;
        bubble.appendChild(mTag);
      }

      wrap.appendChild(bubble);
      chat.appendChild(wrap);
      chat.scrollTop = chat.scrollHeight;

      if (role === 'faixa' || role === 'luna') {
        memory.push({ role, text, data: time });
        saveMem();
      }
    }

    /* ==================================================================== */
    /* ENVIO & PROCESSAMENTO                                                */
    /* ==================================================================== */
    async function handleSend() {
      const input = document.getElementById('msgInput');
      const text = input.value.trim();
      const atts = [...currentAttachments];

      if ((!text && atts.length === 0) || isThinking) return;

      input.value = '';
      currentAttachments = [];
      renderAttachBar();

      renderMessage('faixa', text || '(anexo)');

      // Comandos de sistema
      if (text === '!ajuda') {
        renderMessage('sistema', `Comandos disponíveis:\n• !pergunta <msg>\n• !pedagogo <tema>\n• !bussola <dúvida>\n• !aprender <fato>\n• !estrategia <tema>\n• !psicologia <tema>\n• !codigo <pedido>\n• !matematica <conta>\n• !blindagem <risco>\n• !imagem <prompt>\n• !backup\n• !limpar\n• !ajuda`);
        return;
      }
      if (text === '!backup') { exportMem('full'); return; }
      if (text === '!limpar') { clearAllMem(); return; }

      // Comandos de imagem (fal.ai)
      if (text.startsWith('!imagem ')) {
        const prompt = text.replace('!imagem ', '').trim();
        if (!config.falKey) {
          renderMessage('sistema', 'FAL_KEY ausente. Configure em ⚙️.');
          openModal('cfgModal');
          return;
        }
        isThinking = true;
        try {
          const url = await callFalImage(config.falKey, prompt);
          lastGeneratedImageUrl = url;
          renderMessage('luna', `Imagem gerada para: "${prompt}"`, { imageUrl: url, model: 'fal-ai/flux/schnell' });
        } catch (e) {
          renderMessage('sistema', `Erro ao gerar imagem: ${e.message}`);
        } finally {
          isThinking = false;
        }
        return;
      }

      // Validação de modo direto
      let mode = 'normal';
      let prompt = text;

      for (const m of ['pedagogo', 'bussola', 'aprender', 'estrategia', 'psicologia', 'codigo', 'matematica', 'blindagem']) {
        if (text.startsWith(`!${m} `)) {
          mode = m === 'codigo' ? 'code' : m;
          prompt = text.replace(`!${m} `, '');
          break;
        }
      }
      if (text.startsWith('!pergunta ')) prompt = text.replace('!pergunta ', '');
      if (config.learn) mode = 'aprender';

      if (mode === 'normal' && !config.direct && !text.startsWith('!') && atts.length === 0) {
        renderMessage('sistema', 'Modo direto desligado. Use "!" antes da mensagem ou ligue o botão ⚡ DIRETO.');
        return;
      }

      if (!config.geminiKey) {
        renderMessage('sistema', 'GEMINI_KEY ausente. Abra ⚙️ e cole sua chave do Google AI Studio.');
        openModal('cfgModal');
        return;
      }

      // Monta Prompt Contextualizado com Memória Viva
      const memBlock = memory.slice(-30).map(m => `[${m.data}] ${m.role === 'faixa' ? 'FAIXA' : 'NOCT'}: ${m.text}`).join('\n') || '(primeira conversa)';
      const fullSystem = `${BASE_SYSTEM}\n\n${MODE_DIRECTIVES[mode] || ''}\n\n[MEMÓRIA VIVA REAL]\n${memBlock}\n\nPERGUNTA DO FAIXA: ${prompt || '(analise os anexos)'}`;

      const parts = [{ text: fullSystem }];
      for (const a of atts) {
        if (a.mime.startsWith('image/')) {
          parts.push({ inlineData: { mimeType: a.mime, data: a.data } });
        } else if (a.text) {
          parts.push({ text: `\n[ANEXO: ${a.name}]\n${a.text.slice(0, 15000)}` });
        }
      }

      const body = {
        contents: [{ role: 'user', parts }],
        generationConfig: { temperature: 0.6, maxOutputTokens: 4096 }
      };

      const modelsList = config.models.split(',').map(m => m.trim()).filter(Boolean);

      isThinking = true;
      document.getElementById('btnSend').innerText = '...';

      try {
        const res = await callGeminiEngine(config.geminiKey, modelsList, body, config.fast3s);
        renderMessage('luna', res.answer, { model: res.model, fallback: res.fallback });
        speak(res.answer);
      } catch (err) {
        renderMessage('sistema', `Falha: ${err.message}`);
      } finally {
        isThinking = false;
        document.getElementById('btnSend').innerText = 'ENVIAR';
      }
    }

    /* ==================================================================== */
    /* ANEXOS & MICROFONE                                                   */
    /* ==================================================================== */
    document.getElementById('btnAttach').onclick = () => document.getElementById('fileInput').click();
    document.getElementById('fileInput').onchange = (e) => {
      Array.from(e.target.files).forEach(f => {
        const r = new FileReader();
        if (f.type.startsWith('image/')) {
          r.onload = ev => {
            currentAttachments.push({ name: f.name, mime: f.type, data: ev.target.result.split(',')[1] });
            renderAttachBar();
          };
          r.readAsDataURL(f);
        } else {
          r.onload = ev => {
            currentAttachments.push({ name: f.name, mime: f.type || 'text/plain', text: ev.target.result });
            renderAttachBar();
          };
          r.readAsText(f);
        }
      });
      e.target.value = '';
    };

    function renderAttachBar() {
      const bar = document.getElementById('attachBar');
      bar.innerHTML = '';
      currentAttachments.forEach((a, i) => {
        const chip = document.createElement('div');
        chip.className = 'attach-chip';
        chip.innerHTML = `<span>${a.mime.startsWith('image/')?'🖼️':'📄'} ${a.name}</span><button onclick="removeAttach(${i})">✕</button>`;
        bar.appendChild(chip);
      });
    }
    window.removeAttach = (idx) => { currentAttachments.splice(idx, 1); renderAttachBar(); };

    // Microfone
    const btnMic = document.getElementById('btnMic');
    btnMic.onclick = () => {
      const SR = window.SpeechRecognition || window.webkitSpeechRecognition;
      if (!SR) return alert('Reconhecimento de voz não suportado neste navegador. Use o Google Chrome.');
      if (recognition) { recognition.stop(); return; }

      recognition = new SR();
      recognition.lang = 'pt-BR';
      recognition.onstart = () => btnMic.classList.add('recording');
      recognition.onend = () => { btnMic.classList.remove('recording'); recognition = null; };
      recognition.onresult = (ev) => {
        const t = ev.results[0][0].transcript;
        const inp = document.getElementById('msgInput');
        inp.value = inp.value ? `${inp.value} ${t}` : t;
      };
      recognition.start();
    };

    /* ==================================================================== */
    /* MODAIS, BACKUP & CONFIG                                              */
    /* ==================================================================== */
    function openModal(id) { document.getElementById(id).style.display = 'flex'; }
    function closeModal(id) { document.getElementById(id).style.display = 'none'; }
    window.closeModal = closeModal;

    document.getElementById('btnCfg').onclick = () => {
      document.getElementById('cfgGeminiKey').value = config.geminiKey;
      document.getElementById('cfgFalKey').value = config.falKey;
      document.getElementById('cfgModels').value = config.models;
      document.getElementById('cfgProfile').value = config.profile;
      document.getElementById('cfgName').value = config.personaName;
      document.getElementById('cfg3s').checked = config.fast3s;
      document.getElementById('cfgCrt').checked = config.crt;
      openModal('cfgModal');
    };

    function saveSettings() {
      config.geminiKey = document.getElementById('cfgGeminiKey').value.trim();
      config.falKey = document.getElementById('cfgFalKey').value.trim();
      config.models = document.getElementById('cfgModels').value.trim();
      config.profile = document.getElementById('cfgProfile').value;
      config.personaName = document.getElementById('cfgName').value.trim();
      config.fast3s = document.getElementById('cfg3s').checked;
      config.crt = document.getElementById('cfgCrt').checked;
      saveCfg();
      applyUI();
      closeModal('cfgModal');
    }
    window.saveSettings = saveSettings;

    // Memória Modal
    document.getElementById('btnMem').onclick = () => {
      const list = document.getElementById('memList');
      list.innerHTML = memory.length === 0 ? '<p style="color:var(--text-dim); text-align:center;">Vazio.</p>' : '';
      memory.slice().reverse().forEach(m => {
        const item = document.createElement('div');
        item.style.padding = '8px'; item.style.border = '1px solid var(--border)'; item.style.marginBottom = '6px';
        item.innerHTML = `<div style="display:flex; justify-content:space-between; font-size:10px; color:var(--text-dim);"><span>${m.role.toUpperCase()}</span><span>${m.data}</span></div><div style="margin-top:4px;">${m.text}</div>`;
        list.appendChild(item);
      });
      openModal('memModal');
    };

    function exportMem(mode) {
      const data = mode === 'context30' ? memory.slice(-30) : memory;
      const blob = new Blob([JSON.stringify(data, null, 2)], { type: 'application/json' });
      const a = document.createElement('a');
      a.href = URL.createObjectURL(blob);
      a.download = `noct_memoria_${mode}_${new Date().toISOString().slice(0,10)}.json`;
      a.click();
    }
    window.exportMem = exportMem;

    function importMem(e) {
      const f = e.target.files?.[0];
      if (!f) return;
      const r = new FileReader();
      r.onload = ev => {
        try {
          const parsed = JSON.parse(ev.target.result);
          if (Array.isArray(parsed)) {
            memory = parsed.slice(-500);
            saveMem();
            alert(`Memória importada: ${memory.length} itens.`);
            closeModal('memModal');
          }
        } catch (err) { alert('Arquivo JSON inválido.'); }
      };
      r.readAsText(f);
    }
    window.importMem = importMem;

    function clearAllMem() {
      if (confirm('Limpar toda a memória viva do NOCT?')) {
        memory = [];
        saveMem();
        renderMessage('sistema', 'Memória apagada.');
        closeModal('memModal');
      }
    }
    window.clearAllMem = clearAllMem;

    // Toggles de Toolbar
    const btnLearn = document.getElementById('btnLearn');
    const btnDirect = document.getElementById('btnDirect');
    btnLearn.onclick = () => { config.learn = !config.learn; saveCfg(); applyUI(); };
    btnDirect.onclick = () => { config.direct = !config.direct; saveCfg(); applyUI(); };

    function applyUI() {
      btnLearn.classList.toggle('active-learn', config.learn);
      btnDirect.classList.toggle('active-direct', config.direct);
      document.getElementById('crtOverlay').style.display = config.crt ? 'block' : 'none';
      document.querySelector('.app').classList.toggle('crt-glow', config.crt);
      document.getElementById('memCount').innerText = `${memory.length}/500`;
    }

    // Tecla Enter
    document.getElementById('msgInput').onkeydown = (e) => {
      if (e.key === 'Enter' && !e.shiftKey) {
        e.preventDefault();
        handleSend();
      }
    };
    document.getElementById('btnSend').onclick = handleSend;

    // Inicialização
    applyUI();
    saveMem();
  </script>
</body>
</html>