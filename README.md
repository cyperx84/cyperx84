<p align="center">
  <img src="https://img.shields.io/badge/OpenClaw-Ecosystem-orange?style=flat-square&logo=robot&logoColor=white" alt="OpenClaw Ecosystem">
  <img src="https://img.shields.io/badge/Go-blue?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/CLI--first-black?style=flat-square&logo=gnometerminal&logoColor=white" alt="CLI-first">
</p>

# Hey, I'm CyperX 👋

I build developer tools around **[OpenClaw](https://github.com/openclaw/openclaw)** — an open-source AI agent platform for orchestrating multiple coding agents, models, and workflows from the terminal.

My work lives at the intersection of **multi-model AI orchestration** and **CLI-first developer tooling**. If it runs in tmux, speaks Go, and talks to LLMs, I'm probably interested.

---

## 🧠 OpenClaw Ecosystem

Tools I've built and maintain around OpenClaw:

<table>
<tr>
<td width="33%">

### [clawforge](https://github.com/cyperx84/clawforge)
Agent swarm workflow — spawn, monitor, review, and manage fleets of coding agents from the terminal.

`brew install cyperx84/tap/clawforge`

</td>
<td width="33%">

### [multiplan](https://github.com/cyperx84/multiplan)
4-model parallel planning with eval framework. Run tasks through Claude, Gemini, Codex, and GLM-5 simultaneously with lens-based prompts. Synthesise the best plan from all four.

`brew install cyperx84/tap/multiplan`

</td>
<td width="33%">

### [clwatch](https://github.com/cyperx84/clwatch)
Track changelog updates across AI coding agent harnesses — Claude Code, Codex, Gemini CLI, OpenCode, and more.

`brew install cyperx84/tap/clwatch`

</td>
</tr>
<tr>
<td width="33%">

### [content-breakdown](https://github.com/cyperx84/content-breakdown)
Source-to-action content breakdown CLI. Turn any article, video, or doc into structured findings, ranked ideas, and actionable notes.

`brew install cyperx84/tap/content-breakdown`

</td>
<td width="33%">

### [changelogs.info](https://github.com/cyperx84/changelogs-info)
AI coding tool changelog aggregator. Personalised filtering, breaking change alerts, cost calculators, and migration guides for the tools you actually use.

[changelogs.info](https://changelogs.info)

</td>
<td width="33%">

### [homebrew-tap](https://github.com/cyperx84/homebrew-tap)
Homebrew tap for all my tools. One tap, clean installs.

`brew tap cyperx84/tap`

</td>
</tr>
</table>

---

## 🔧 How It Fits Together

```
┌──────────────────────────────────────────────────┐
│                    OpenClaw                       │
│           (AI agent orchestration)                │
│                                                   │
│  ┌──────────┐  ┌──────────┐  ┌──────────────┐   │
│  │clawforge │  │multiplan │  │  clwatch     │   │
│  │ agent    │  │ 4-model  │  │  changelog   │   │
│  │ swarms   │  │ planning │  │  tracker     │   │
│  └──────────┘  └──────────┘  └──────────────┘   │
│  ┌──────────┐  ┌──────────┐  ┌──────────────┐   │
│  │content-  │  │changelogs│  │  homebrew    │   │
│  │breakdown │  │   .info  │  │    tap       │   │
│  └──────────┘  └──────────┘  └──────────────┘   │
└──────────────────────────────────────────────────┘
        ↕               ↕               ↕
     Claude         Gemini          Codex          GLM-5
```

**multiplan** generates plans, **clawforge** executes them with agent swarms, **clwatch** keeps track of upstream changes, and **content-breakdown** turns any content into structured action.

---

## 🛠 Other Projects

- **[claude-skills-mental-models](https://github.com/cyperx84/claude-skills-mental-models)** — Mental models & cognitive frameworks as Claude Code skills
- **[openclaw-tui-dashboard](https://github.com/cyperx84/openclaw-tui-dashboard)** — TUI dashboard for OpenClaw monitoring
- **[tts-toolkit](https://github.com/cyperx84/tts-toolkit)** — Extensible text-to-speech toolkit with voice cloning
- **[dotfiles](https://github.com/cyperx84/dotfiles)** — macOS dev environment (Ghostty, tmux, Neovim, Aerospace)

---

## 📦 Install

All tools are available via Homebrew:

```bash
brew tap cyperx84/tap
brew install clawforge multiplan clwatch content-breakdown
```

Or individually via `go install`:

```bash
go install github.com/cyperx84/clawforge@latest
go install github.com/cyperx84/multiplan@latest
go install github.com/cyperx84/clwatch@latest
go install github.com/cyperx84/content-breakdown@latest
```

---

<p align="center">
  <i>Built with OpenClaw · Powered by too many LLMs · Runs in tmux</i>
</p>
