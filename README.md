<div align="center">

# 🐙 BBARIT Terminal (빠릿터미널)

### The all-in-one AI vibe-coding IDE — every AI agent, every dev tool, one native terminal.

Run **Claude · Codex · Gemini · Kimi · Qwen · OpenCode · Ollama** side by side, pair two of them into a self-reviewing dev team, and ship — all from a fast native desktop app.

Free with GitHub sign-in · auto-updating · built with Tauri + Rust + React.

### ⬇️ Download

| Platform | Get it |
| --- | --- |
| 🍎 **macOS** (Apple Silicon) | [Latest release](https://github.com/bbarit/terminal/releases/latest) · [bbarit.com](https://bbarit.com) |
| 🪟 **Windows** 10/11 | [Latest release](https://github.com/bbarit/terminal-win/releases/latest) · [bbarit.com](https://bbarit.com) |

> macOS repo: **[bbarit/terminal](https://github.com/bbarit/terminal)** · Windows repo: **[bbarit/terminal-win](https://github.com/bbarit/terminal-win)**

</div>

---

## Why BBARIT?

Most "AI IDEs" lock you into one model and one workflow. BBARIT is a **native terminal** that puts *every* AI coding agent in one place, gives them real tools (PTY, git, editors, databases, MCP), and lets them **work as a team** — with a knowledge base that gets smarter every session.

If you live in the terminal and want AI that actually does the work, this is your cockpit.

---

## ✨ Headline: 🦌 Broker Agent — your AI pair-dev team

Press one button and BBARIT opens **two real terminals** — a **Developer** (e.g. Claude) and a **Reviewer** (e.g. Codex) — and acts as the **broker** between them.

- The developer implements and **tests its own work**; the reviewer **continuously reviews** the `git diff` (Linus-style: direct, specific).
- They never screen-scrape each other — they coordinate purely through **git diffs** and the **Karpathy Wiki**, so everything is tracked and reproducible.
- **Self-improving:** recurring review findings are promoted into permanent design rules, so the same mistakes get caught earlier next time.
- **Tiered knowledge:** project wiki → global wiki → *other projects' code* when stuck, learning your own patterns.
- **You stay in control:** agents propose; **merge & deploy require your approval**.
- Pick any installed CLI for either role; runs in an isolated git worktree so you can run several features at once and merge later.

> One click → a Claude+Codex pair that designs, builds, tests, reviews, and records — while you just give the goal.

---

## 🤖 Multi-AI terminals

- First-class support for **Claude Code, Codex, Gemini, Kimi, Qwen, Cursor, OpenCode, Ollama** — each in its own PTY session with independent model/flags/mode.
- Per-project agent settings, autonomy modes (auto-accept / full-auto / yolo), and one-key switching.
- **AI Roundtable** and orchestra/workflow pipelines for multi-model debate and fan-out.

## 🖥️ Terminal & editor

- Real **PTY** terminal (portable-pty + Rust) with **WebGL** rendering, Unicode 11, ligatures.
- Split panes (resizable tree layout), tabs, per-project themes & fonts.
- First-class **CJK/IME** input (Korean/Chinese/Japanese) done right.
- Built-in editor with **13+ file types**, file tree, quick open, reveal-in-explorer.

## 🛠️ Developer tools

- **Git panel** — status, diff, history, branches, stashes, worktrees, merge.
- **Code search** — hybrid BM25 + semantic (semble) over your source.
- **Task management** — Kanban, Todo, and Gantt planner, global across projects.
- **MCP** — connect Model Context Protocol servers; built-in browser MCP bridge.
- **Database** — MySQL & PostgreSQL with schema browsing.
- **PM2 / process** monitoring and a server hub.

## 📚 Knowledge that compounds

- **Karpathy Wiki** — a structured, two-tier (project + global) knowledge base your agents read first and write back to.
- **Notes / knowledge graph** — markdown vault with wikilinks, backlinks, tags, and an Obsidian-style graph view.
- **Skills library** — thousands of curated skills, GitHub skill-pack import, and the built-in **Karpathy guidelines** pack (think-before-coding, simplicity, surgical changes, goal-driven).
- **Self-improving harness** — background review distills lessons into reusable skills/rules.

## 🔌 Integrations & remote

- **Telegram · Discord · Slack** — mirror terminal I/O and drive sessions remotely.
- **GitHub · Linear** — repo and issue connections.
- **SSH** — full remote-project terminals.
- **AutoResearch** — Karpathy-style autonomous ML experiment panel.

## 🎨 Media & more

- Screen capture (region select), clipboard image paste straight into the terminal.
- Native video editor panel, design/media generation hooks.
- Command palette, fully configurable keybindings, automation workflows.

---

## 💻 Requirements

| | |
| --- | --- |
| **macOS** | Apple Silicon (M1 or later) |
| **Windows** | 10 / 11 (64-bit) |
| **AI CLIs** | Install the agents you want (Claude Code, Codex, Gemini, etc.) — BBARIT drives them |
| **License** | Free — sign in with GitHub |

## 📥 Install

1. Download the latest build for your platform:
   - 🍎 **macOS (Apple Silicon)** → [github.com/bbarit/terminal/releases/latest](https://github.com/bbarit/terminal/releases/latest)
   - 🪟 **Windows 10/11** → [github.com/bbarit/terminal-win/releases/latest](https://github.com/bbarit/terminal-win/releases/latest)
   - or grab either from **[bbarit.com](https://bbarit.com)**
2. Launch and sign in with GitHub (free license).
3. Open a project folder and start a terminal — or press the **🦌 Broker Agent** button to spin up an AI pair.

Auto-updates are built in (Tauri updater) — you'll always get the latest.

## ❓ FAQ

- **Do I need an API key?** You use the AI **CLIs** you already have installed; BBARIT runs them in real terminals.
- **Which agents can the Broker Agent pair use?** Any installed CLI — Claude, Codex, Gemini, Kimi, Qwen, Ollama, and more (configurable in Settings).
- **Will it touch my repo without asking?** No — the Broker Agent never merges or deploys without your approval, and it sets up git (with a notice) only when needed for review.
- **My project has no git — does review still work?** The Broker Agent offers to initialize git so diff-based review works, and tells you before it does.

## 🆘 Support

- Issues: this repository's GitHub Issues
- Contact: keke@kekeappa.com

---

<div align="center">

Maintained by Tenmiles Inc. · Built for solo developers who ship with AI.

🍎 [bbarit/terminal](https://github.com/bbarit/terminal) · 🪟 [bbarit/terminal-win](https://github.com/bbarit/terminal-win) · 🌐 [bbarit.com](https://bbarit.com)

</div>
