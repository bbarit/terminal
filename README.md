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

## 🎥 See it in action

[![BBARIT Terminal — intro & demo](https://img.youtube.com/vi/5IBCLQHED3M/hqdefault.jpg)](https://youtu.be/5IBCLQHED3M)

▶️ **[Watch the intro & demo](https://youtu.be/5IBCLQHED3M)**

<details>
<summary><b>📖 Full product tour (English walkthrough)</b></summary>

**Projects, fast** — Open projects from local disk, over SSH, or open a server directly. All your projects sit in one place, laid out on the left; jump between them with a shortcut (Ctrl/Cmd+Shift). **Ctrl+P quick open searches across *all* projects** (not just the current one) and is extremely fast. Reorder by drag-and-drop, pin favorites to the top, restyle instantly.

**Layouts & monitor mode** — Switch to terminal-only, rearrange terminal panes (move/add/remove), see live-terminal dots. New **Monitor mode** shows everything at a glance — like CCTV for your services — hopping across projects in real time via shortcuts.

**Every file viewer/editor built in** — Markdown-first (viewer with code blocks, tables, images, color-customizable emoji), Mermaid charts, HTML viewer, images (BMP/GIF/ICO/JPG/PNG), video (MP4), audio (MP3), **PDF with editing**, **Word/PowerPoint/Excel** (Excel functions too), **EPUB** whole-book viewer/creator, SQLite, and all code editors (JSON tree view, JS, Java, text…). You never leave the app to open a file.

**Knowledge: Karpathy Wiki & skills** — Auto-generates a Karpathy-style Wiki; skills library you can run; **commands saved to a database**; "summarize recent activity" reminds you what you did; clear-input button; send a dependency-tree structure diagram to the agent. Works with Claude, Codex, OpenCode, Gemini, Kimi, Ollama (local too).

**Git, tasks & automation** — Full Git panel (history, branches, remotes, stash, tags; fetch/pull/push). Global search/quick open. **Gantt (tree) chart** linking tasks to projects/terminals. **Kanban** that **imports GitHub/Linear issues** → send a card to the terminal so the agent fixes it (one-click support automation), with doc/project linking and drag-and-drop.

**Servers, hub & voice** — Server monitoring (per-process logs, memory/CPU, health/network/security/docker/disk checks). Hub shows Linear/Slack/GitHub at once. Voice input via right Alt/Option key (macOS). Skills Studio installs skill packs (180+) in one click.

**Settings** — Font size, scrollback (fewer = faster), max terminals per row, themes, editor options, fully customizable keybindings, hub connections (Linear/Slack/GitHub) per project or globally.

**Remote access — Web Terminal 🌐** — Click the Web Terminal, copy the link, open it elsewhere in a **browser — even on mobile**. This is remote access: drive your terminal/agents on this machine from anywhere.

**Remote messaging** — Telegram, Discord, Slack (per chat channel, mirror/drive sessions). Language settings included.

*(Translated to English from the founder's Korean intro video.)*

</details>

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

## 📋 Full feature list

<details open>
<summary><b>Everything in the box</b></summary>

**AI agents & orchestration**
- Multi-agent terminals: Claude Code, Codex, Gemini, Kimi, Qwen, Cursor, OpenCode, Ollama, Pi, Reasonix
- 🦌 **Broker Agent** — AI dev↔review pair (git + wiki channel, self-improving, configurable roles, worktree isolation+merge, human approval gate)
- AI Roundtable (multi-model debate), Orchestra / workflow pipelines (fan-out, decompose, parallel)
- Per-project agent flags, models, autonomy modes (normal / auto-accept / full-auto / yolo)

**Terminal & editor**
- Native PTY (portable-pty + Rust), WebGL renderer, Unicode 11, ligatures, ~30fps
- Resizable split panes (tree layout), tabs, multi-project tabs with per-project themes & fonts
- Built-in editor (13+ file types), file tree, quick open, drag-drop, reveal in explorer
- First-class CJK/IME (Korean/Chinese/Japanese), command palette, fully configurable keybindings & chords

**Dev tools**
- Git panel (status, diff, history, branches, stashes, tags, worktrees, merge)
- Hybrid code search (BM25 + semantic / semble)
- Kanban board, Todo, Gantt planner (global across projects), issue import
- MCP server connections + built-in browser MCP bridge
- Database: MySQL & PostgreSQL with schema browsing
- PM2 / process monitoring, server Hub, SSH remote projects

**Knowledge & skills**
- Karpathy Wiki — two-tier (project + global) structured knowledge base
- Notes / knowledge base with wikilinks, backlinks, tags, Obsidian-style graph view, templates
- Skills library (thousands curated) + GitHub skill-pack import + Karpathy guidelines pack
- Self-improving harness (background review → durable skills/rules), prompt library
- AutoResearch (Karpathy-style autonomous ML experiment panel)

**Integrations & remote**
- Telegram, Discord, Slack (mirror terminal I/O + remote control)
- GitHub, Linear connections; SSH remote-project terminals
- Generic HTTP proxy (CORS-free) for integrations

**Media & productivity**
- Screen capture (region select), clipboard image paste into terminal
- Native video editor, design/media generation hooks, video-to-prompt & face-swap skills
- OS notifications, completion sounds, auto-updater (Tauri), collab session sharing

</details>

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
