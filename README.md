# AgentTaste: Universal Agent Skills & Taste Rules for AI Coding

> **Stop AI Slop UI, Monolithic Spaghetti Code & Generic Design.**  
> Curated, production-tested system prompts and `SKILL.md` rules for **Cursor**, **ChatGPT**, **Claude Code**, **Grok (xAI)**, **GitHub Copilot**, **DeepSeek**, **v0**, **Windsurf**, and **Antigravity**.

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![Cursor](https://img.shields.io/badge/Cursor-.cursorrules%20Ready-3b82f6.svg)](https://agenttaste.dev)
[![ChatGPT & Canvas](https://img.shields.io/badge/ChatGPT-Canvas%20Ready-74aa9c.svg?logo=openai)](https://agenttaste.dev)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Compatible-d97706.svg?logo=anthropic)](https://agenttaste.dev)
[![Grok (xAI)](https://img.shields.io/badge/Grok-xAI%20Ready-000000.svg?logo=x)](https://agenttaste.dev)
[![GitHub Copilot](https://img.shields.io/badge/Copilot-Instructions-1f2937.svg?logo=github)](https://agenttaste.dev)
[![DeepSeek](https://img.shields.io/badge/DeepSeek-R1%20%2F%20V3-4f46e5.svg)](https://agenttaste.dev)
[![v0 by Vercel](https://img.shields.io/badge/v0.dev-Generative%20UI-black.svg?logo=vercel)](https://agenttaste.dev)
[![Official Registry](https://img.shields.io/badge/Full%20Registry-AgentTaste.dev-purple.svg)](https://agenttaste.dev)

---

## ⚡ The Problem: AI Slop by Default

Whether you ask **Cursor**, **ChatGPT (GPT-4o)**, **Grok 3 (xAI)**, **Claude 3.7 Sonnet**, or **DeepSeek-R1**, autonomous models default to the same tired aesthetic and architectural habits:

1. **Cliché UI Slop**: 3 identical white cards, childish drop shadows, purple-to-pink gradient titles, and generic Lucide icons (`Rocket 🚀`, `Star ⭐`, `Shield 🛡️`).
2. **Monolithic Architecture**: Autonomous coding agents dump 800-line monolithic files with raw database queries embedded inside React render loops.
3. **Zero Conversion Copy**: Landing pages sound like corporate committee jargon instead of crisp, high-converting Silicon Valley products.

**AgentTaste** injects taste, structural boundaries, and modern design systems directly into your AI context window.

---

## 🌐 Universal Compatibility Matrix

AgentTaste rules are pure markdown instructions designed to work across all major LLMs and development tools:

| LLM / Platform | Integration Method | Supported Features |
| :--- | :--- | :--- |
| **Cursor** | `.cursorrules` or `.cursor/rules/*.mdc` | Real-time inline completions & frontend architectural constraints |
| **ChatGPT & Canvas** | Custom Instructions / System Prompt | Enforces Clean UI & Modern Bento Grids in Canvas code |
| **Grok (xAI)** | Custom System Prompt / Grok API | Steers Grok 2 & Grok 3 toward Silicon Valley aesthetic standards |
| **Claude Code** | `.claude/skills/*.md` or `CLAUDE.md` | Auto-invoked skill rules, subagent guardrails |
| **GitHub Copilot** | `.github/copilot-instructions.md` | Workspace-wide code quality & styling standards |
| **DeepSeek (R1 / V3)** | System Prompt / Ollama / Cline | Steers raw reasoning power toward strict UI taste |
| **v0 by Vercel** | Project System Prompt / Custom Rules | Replaces default v0 cards with Linear-grade dark UI |
| **Windsurf & Cline** | `.windsurfrules` / `.clinerules` | Agentic workflow automation & decoupled file boundaries |
| **Antigravity (Google)**| `.gemini/antigravity/builtin/skills` | Native AGY skill directory integration |

---

## 🎁 Included Open-Source Core Skills

This repository provides 3 high-impact foundational skills for immediate use:

| Skill | Solves | Target Environments | Source File |
| :--- | :--- | :--- | :--- |
| **`linear-dark-ui`** | Enforces `#09090b` zinc hierarchy, 1px micro-border glows, bans bright white cards. | Cursor, ChatGPT, Grok, Claude Code, Copilot, v0 | [`skills/linear-dark-ui.md`](./skills/linear-dark-ui.md) |
| **`anti-generic-components`** | Intercepts repetitive 3-column cards, forces 65/35 asymmetric bento grids. | Cursor, ChatGPT Canvas, Grok, Claude Code, DeepSeek | [`skills/anti-generic-components.md`](./skills/anti-generic-components.md) |
| **`claude-clean-arch-lite`** | Max 250 lines per file, strict server/client boundary, isolated Zod contracts. | Cursor, Claude Code, Copilot, Windsurf | [`skills/claude-clean-arch-lite.md`](./skills/claude-clean-arch-lite.md) |

---

## 🚀 Quick Start Guide

### 1. Cursor (`.cursorrules` & `.cursor/rules/*.mdc`)
Copy the markdown rules directly into `.cursorrules` in your project root, or save modular files inside `.cursor/rules/`:
```bash
mkdir -p .cursor/rules
curl -o .cursor/rules/linear-ui.mdc https://raw.githubusercontent.com/nykee/agenttaste-skills/main/skills/linear-dark-ui.md
```

### 2. Claude Code
Install directly into your workspace:
```bash
mkdir -p .claude/skills
curl -o .claude/skills/linear-dark-ui.md https://raw.githubusercontent.com/nykee/agenttaste-skills/main/skills/linear-dark-ui.md
```
Or append rule directives to your `CLAUDE.md`.

### 3. Grok (xAI)
Prepend the skill rules into your Grok prompt on X or via the xAI API:
> *"Act as an expert frontend designer. Apply the following design constraints to all generated React and Tailwind code: [Paste SKILL.md rules]"*

### 4. ChatGPT & Canvas
- **ChatGPT Canvas / Regular Chat**: Prepend the content of any `skills/*.md` file to your opening prompt.
- **Custom Instructions**: Paste into your account's *"How would you like ChatGPT to respond?"* settings.
- **Custom GPTs**: Add into the GPT Instructions panel for a dedicated *"AgentTaste UI Builder"* assistant.

### 5. GitHub Copilot
Create `.github/copilot-instructions.md` in your repository root and paste the skill rules. Copilot will automatically apply the design standards to all inline completions and chat suggestions.

### 6. v0 by Vercel (`v0.dev`)
Paste `linear-dark-ui.md` or `anti-generic-components.md` into the v0 project rules or the start of your design prompt to override v0's standard card layouts.

### 7. DeepSeek, Windsurf, & Cline
- **Windsurf**: Save to `.windsurfrules`.
- **Cline / Roo Code**: Save to `.clinerules`.
- **DeepSeek (via Ollama / OpenRouter)**: Use as the system prompt parameter.

---

## 💎 Need the Full Production Registry?

Visit the official platform at **[AgentTaste.dev](https://agenttaste.dev)**:

- 🌟 **Marc Lou Conversion Engine**: Founder-led copy, impulse checkout layout, 10-second proof hooks.
- 🌟 **Stripe Fluid Micro-Interactions**: Hardware-accelerated CSS physics, spring curves, zero-CLS transitions.
- 🌟 **Product Hunt #1 Launch Pack**: 60-character taglines, viral maker comments, PST launch sequencing.
- 🌟 **Stitch Minimalist Taste**: Asymmetric bento grids, breathing ambient gradients, luxury typography rhythm.
- 🌟 **Full Pro Bundle**: 50+ curated production skills with interactive Before/After diffs and instant CLI installer (`npx agenttaste-cli`).

👉 **[Explore Full Registry & Founder Lifetime Pass on AgentTaste.dev →](https://agenttaste.dev)**

---

## 📄 License

MIT License. Open-source contribution to elevate AI code aesthetics worldwide.
