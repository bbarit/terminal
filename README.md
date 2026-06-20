<div align="center">

# 🐙 BBARIT Terminal (빠릿터미널)

### The Ultimate AI Vibe-Coding IDE — every AI agent, every dev tool, one native terminal.

> **궁극의 AI 바이브코딩** · *formerly **Octo Terminal** (구 옥토터미널)*

Run **Claude · Codex · Gemini · Kimi · Qwen · OpenCode · Ollama** side by side, pair two of them into a **self-reviewing dev team that ships while you sleep**, and never leave the terminal — all from a fast native desktop app.

Free with GitHub sign-in · auto-updating · built with Tauri + Rust + React.

### ⬇️ Download

| Platform | Get it |
| --- | --- |
| 🍎 **macOS** (Apple Silicon) | [Latest release](https://github.com/bbarit/terminal/releases/latest) · [bbarit.com](https://bbarit.com) |
| 🪟 **Windows** 10/11 | [Latest release](https://github.com/bbarit/terminal-win/releases/latest) · [bbarit.com](https://bbarit.com) |

> macOS repo: **[bbarit/terminal](https://github.com/bbarit/terminal)** · Windows repo: **[bbarit/terminal-win](https://github.com/bbarit/terminal-win)**

</div>

<!-- SEO: octo terminal, octoterminal, 옥토터미널, bbarit terminal, 빠릿터미널, ultimate ai vibe coding, vibe coding terminal, ai terminal, ai coding ide, claude code terminal, codex terminal, gemini cli, kimi cli, ollama terminal, ai pair programming, autonomous ai coding, ai dev review pair, multi ai terminal, ai agent orchestration, mcp server client, ssh terminal, web terminal cloudflare, tauri rust terminal, xterm webgl, monaco editor ide, knowledge base wiki, kanban gantt, nanobanana ai image studio, macos terminal, windows terminal, developer productivity, ship with ai -->

---

## Why BBARIT?

Most "AI IDEs" lock you into one model and one workflow. BBARIT is a **native terminal** that puts *every* AI coding agent in one place, gives them real tools (PTY, git, editors, databases, MCP, a browser), and lets them **work as a team** — coordinated by a transparent **mechanical broker**, backed by a knowledge base that gets smarter every session.

If you live in the terminal and want AI that actually *does the work* — designs, builds, tests, reviews, and merges — this is your cockpit.

---

## 🎥 See it in action

[![BBARIT Terminal — intro & demo](https://img.youtube.com/vi/5IBCLQHED3M/hqdefault.jpg)](https://youtu.be/5IBCLQHED3M)

▶️ **[Watch the intro & demo](https://youtu.be/5IBCLQHED3M)**

---

## ✨ Headline: 🦌 Broker Agent — your autonomous AI dev/review team

Press one button and BBARIT opens **two real terminals** — a **Developer** (e.g. Claude) and a **Reviewer** (e.g. Codex) — and runs a **mechanical broker** between them that mediates the whole dev↔review loop. You give the goal; the pair designs, builds, tests, reviews, and merges.

**How the loop works**

1. The **developer** implements and **tests its own work**, keeps a project wiki, and appends a one-line `DONE` when a unit is genuinely finished.
2. The **broker** sees that signal, reads the `git diff`, **judges it mechanically** (source-growth, code-graph blast radius, sensitivity patterns, requirements progress — *no extra LLM cost*), and hands the change to the reviewer.
3. The **reviewer** reviews (Linus-style: direct, specific) and replies `APPROVED` or `REWORK: …` — and **owns the rework loop** until it's right.
4. On `APPROVED`, the broker **auto-commits and merges the isolated branch** (only if git checks pass); a failed merge is escalated to you.

**What makes it different**

- **No screen-scraping.** The two agents coordinate purely through **git** and the **Karpathy Wiki** — everything is tracked, reproducible, and reviewable.
- **The broker does the reading for them.** It reads diffs and review notes and **delivers the content directly** to each agent, so they spend tokens on work, not on opening files.
- **Worktree isolation.** Each harness runs on its own git branch + worktree, so it never pollutes your working tree — run **several features in parallel** and merge them later.
- **Multi-harness manager.** A full-screen workspace with a **project → harness tree**: spin up many dev/review pairs across projects, switch between them, each with its **own live status window** (Working / Done), broker log, and two terminals.
- **Hot-swap models any time.** Change the developer or reviewer agent mid-session; the new agent reads the wiki + git and **continues** the in-progress work.
- **Session persistence.** Harnesses are saved and **auto-restore on reopen/restart**, continuing exactly where they left off — including queued auto-merges.
- **Requirements traceability (RTM).** Every requirement is a tracked row, verified against *real* code + tests before anything is called done.
- **Self-improving.** Recurring review findings are promoted into permanent design rules, so the same mistakes get caught earlier next time.
- **Tiered knowledge.** Project wiki → global wiki → *other projects' code* when stuck — learning your own patterns.
- **You stay in control.** Agents propose; **merge & deploy require your approval.**

> One click → a Claude+Codex pair that designs, builds, tests, reviews, and records — while you just give the goal.

---

## 🤖 Multi-AI terminals

- First-class support for **Claude Code, Codex, Gemini, Kimi, Qwen, Cursor, OpenCode, Ollama, Pi, Reasonix** — each in its own PTY session with independent model / flags / autonomy mode.
- Per-project agent settings, autonomy modes (normal / auto-accept / full-auto / yolo), and one-key switching.
- **AI Roundtable** (multi-model debate) and **Orchestra / LangGraph** workflow pipelines for decompose → fan-out → synthesize.

## 🖥️ Terminal & editor

- Real **PTY** terminal (portable-pty + Rust) with **WebGL** rendering, Unicode 11, ligatures, copy-on-select & right-click copy/paste.
- Multi-project, multi-terminal: dozens of projects, each with its own terminals, **resizable split panes** (tree layout), tabs, themes & fonts.
- First-class **CJK / IME** input (Korean / Chinese / Japanese) done right, with UTF-8 shells out of the box.
- Built-in editor (**Monaco** + Vim + Emmet + Prettier) and viewers for **Markdown, PDF (with editing), Word, PowerPoint, Excel, EPUB, SQLite, Mermaid, images, video & audio** — you never leave the app to open a file.

## 🛠️ Developer tools

- **Git panel** — status, diff, history, branches, stashes, tags, worktrees, merge.
- **Code search** — hybrid BM25 + semantic over your source, plus a code-graph (defs / callers / impact).
- **Tasks** — global Kanban, Todo, and a **Gantt planner** that links tasks to projects/terminals; **imports GitHub & Linear issues** → send a card to a terminal so the agent fixes it.
- **MCP** — connect Model Context Protocol servers, with a built-in **browser MCP bridge** + 100+ curated presets.
- **Database** — MySQL & PostgreSQL with schema browsing.
- **PM2 / process** monitoring with AI anomaly detection, and a server Hub.

## 📚 Knowledge that compounds

- **Karpathy Wiki** — a structured, two-tier (project + global) knowledge base your agents read first and write back to; kept small with per-topic files and auto-archiving.
- **Notes / knowledge graph** — markdown vault with wikilinks, backlinks, tags, and an Obsidian-style graph view.
- **Skills library** — thousands of curated skills, GitHub skill-pack import, and a built-in **Karpathy guidelines** pack (think-before-coding, simplicity, surgical changes, goal-driven).

## 🔌 Integrations & remote

- **Web Terminal** — open a full terminal, file explorer, and editor **from any browser** (phone or desktop) over a **Cloudflare tunnel**.
- **Telegram · Discord · Slack** — mirror terminal I/O and drive sessions remotely from your phone (passwords auto-masked).
- **Real-time Collab** — share a room code; **Kanban, notes, chat, browser URL, and bookmarks sync live** across your team via WebSocket + Cloudflare tunnel.
- **GitHub · Linear** unified Hub, full **SSH** remote-project terminals, and a built-in **Chromium browser** with an AI toolbar (inspect, console/network, page→Markdown, AI-fix).

## 🎨 Media, design & more

- **NanoBanana AI Studio** — 16+ design services in one panel (app icons, banners, logos, product/ad images, ad videos, cartoons, interiors, 360° product spins, web-page generation) powered by Gemini / Imagen / Veo.
- Screen capture (region select), clipboard image paste straight into the terminal, native video editor.
- Command palette, fully configurable keybindings (Octo / VSCode / IntelliJ presets), voice input (Whisper), 8 UI languages.

---

## 📋 Full feature list

<details>
<summary><b>Everything in the box</b></summary>

**AI agents & orchestration**
- Multi-agent terminals: Claude Code, Codex, Gemini, Kimi, Qwen, Cursor, OpenCode, Ollama, Pi, Reasonix
- 🦌 **Broker Agent** — autonomous AI dev↔review pair: mechanical broker (no extra LLM cost), git + wiki channel, DONE-signal flow, worktree isolation + headless auto-merge, RTM requirements traceability, live status window, multi-harness manager, hot-swap models, session persistence/auto-resume, self-improving rules, human approval gate
- AI Roundtable (multi-model debate), Orchestra / LangGraph workflow pipelines (decompose, fan-out, parallel, checkpointing)
- Per-project agent flags, models, autonomy modes (normal / auto-accept / full-auto / yolo)

**Terminal & editor**
- Native PTY (portable-pty + Rust), WebGL renderer, Unicode 11, ligatures, UTF-8 shells
- Resizable split panes (tree layout), tabs, multi-project tabs with per-project themes & fonts (75+ themes)
- Copy-on-select, right-click copy/paste, search, click-to-open links
- Monaco editor (Vim, Emmet, Prettier) + viewers: Markdown, PDF (edit), Word, PowerPoint, Excel, EPUB (read & create), SQLite, Mermaid, JSON tree, images, video, audio
- First-class CJK/IME (Korean/Chinese/Japanese), command palette, configurable keybindings & chords

**Dev tools**
- Git panel (status, diff, history, branches, stashes, tags, worktrees, merge)
- Hybrid code search (BM25 + semantic) + code-graph (defs / callers / impact)
- Kanban board, Todo, Gantt planner (global across projects), GitHub/Linear issue import → terminal
- MCP server connections + built-in browser MCP bridge + 100+ presets
- Database: MySQL & PostgreSQL with schema browsing
- PM2 / process monitoring with AI anomaly detection, server Hub, SSH remote projects

**Knowledge & skills**
- Karpathy Wiki — two-tier (project + global) structured knowledge base, per-topic files, auto-archiving
- Notes / knowledge base with wikilinks, backlinks, tags, Obsidian-style graph view, templates
- Skills library (thousands curated) + GitHub skill-pack import + Karpathy guidelines pack
- Self-improving harness (background review → durable rules), prompt library
- AutoResearch (Karpathy-style autonomous ML experiment panel)

**Integrations & remote**
- Web Terminal (browser access to terminal/files/editor via Cloudflare tunnel)
- Real-time Collab (Kanban, notes, chat, browser URL, bookmarks sync) with room codes
- Telegram, Discord, Slack (mirror terminal I/O + remote control)
- GitHub, Linear unified Hub; SSH remote-project terminals; built-in Chromium browser + AI toolbar
- Generic HTTP proxy (CORS-free) for integrations

**Media & productivity**
- NanoBanana AI design studio (16+ services: icons, banners, logos, ads, ad video, cartoons, interiors, 360°, web builder)
- Screen capture (region select), clipboard image paste into terminal, native video editor
- Voice input (Whisper), OS notifications, completion sounds, 8 UI languages
- Auto-updater (Tauri), code-signed builds, collab session sharing

</details>

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

- **Do I need an API key?** You use the AI **CLIs** you already have installed; BBARIT runs them in real terminals. (Some optional studios like NanoBanana use your own Gemini key.)
- **Which agents can the Broker Agent pair use?** Any installed CLI — Claude, Codex, Gemini, Kimi, Qwen, Ollama, and more — and you can hot-swap either role mid-session.
- **Will it touch my repo without asking?** No — the Broker Agent works in an **isolated git worktree** and never merges or deploys without your approval. It only initializes git (with a notice) when needed for review.
- **Can I run more than one AI pair at once?** Yes — the multi-harness manager runs several dev/review pairs in parallel, each isolated and individually monitored.
- **Does it work over SSH / from my phone?** Yes — SSH projects work like local ones, and the Web Terminal + Telegram/Discord/Slack mirroring let you drive sessions from a browser or phone.

## 🆘 Support

- Issues: this repository's GitHub Issues
- Contact: keke@kekeappa.com

---

<div align="center">

Maintained by Tenmiles Inc. · Built for developers who ship with AI.

🍎 [bbarit/terminal](https://github.com/bbarit/terminal) · 🪟 [bbarit/terminal-win](https://github.com/bbarit/terminal-win) · 🌐 [bbarit.com](https://bbarit.com)

</div>
