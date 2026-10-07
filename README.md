# AgentTaste: Universal Agent Skills & Taste Rules for AI Coding

> **Stop AI Slop UI & Monolithic Spaghetti Files.**  
> Curated, battle-tested system prompts and `SKILL.md` rules for **Claude Code**, **Cursor**, **Codex**, **Windsurf**, and **Antigravity**.

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Compatible-indigo.svg)](https://agenttaste.dev)
[![Cursor](https://img.shields.io/badge/Cursor-Rules%20Ready-blue.svg)](https://agenttaste.dev)
[![Official Registry](https://img.shields.io/badge/Full%20Registry-AgentTaste.dev-purple.svg)](https://agenttaste.dev)

---

## ⚡ The Problem: AI Slop by Default

By default, even frontier models (Claude 3.7 Sonnet, GPT-4o, Claude Opus) suffer from default aesthetic habits:
1. **Cliché UI Slop**: AI spits out 3 identical white rectangular cards with purple gradient titles and generic Lucide icons (`Rocket`, `Star`, `Shield`).
2. **Monolithic Architecture**: Autonomous coding agents dump 800-line monolithic files with raw database queries embedded directly inside React render loops.
3. **Weak Copy & Zero Conversion**: Landing pages sound like corporate jargon committees instead of conversion-focused indie products.

**AgentTaste** injects taste, structural constraints, and Silicon Valley design standards into autonomous coding sessions.

---

## 🎁 Included Open-Source Skills

This open-source core repository provides 3 high-impact foundational skills:

| Skill | Target Agents | Key Constraint Solved | Source File |
| :--- | :--- | :--- | :--- |
| **`linear-dark-ui`** | Claude Code, Cursor, Codex | Enforces `#09090b` zinc hierarchy, 1px subtle border glows, bans bright white cards. | [`skills/linear-dark-ui.md`](./skills/linear-dark-ui.md) |
| **`anti-generic-components`** | Claude Code, Cursor, Antigravity | Intercepts repetitive 3-column card rows, forces 65/35 asymmetric bento grids. | [`skills/anti-generic-components.md`](./skills/anti-generic-components.md) |
| **`claude-clean-arch-lite`** | Claude Code, Cursor | Max 250 lines per component, strict server/client boundary, isolated Zod contracts. | [`skills/claude-clean-arch-lite.md`](./skills/claude-clean-arch-lite.md) |

---

## 🚀 Quick Start

### Option 1: Claude Code (Global or Project)
Copy any skill directly into your project's `.claude/skills/` directory or reference it in `CLAUDE.md`:

```bash
mkdir -p .claude/skills
curl -o .claude/skills/linear-dark-ui.md https://raw.githubusercontent.com/nykee/agenttaste-skills/main/skills/linear-dark-ui.md
```

### Option 2: Cursor (`.cursorrules`)
Copy the markdown rules into your root `.cursorrules` file or `.cursor/rules/ui.mdc`.

---

## 💎 Need the Full Production Registry?

Visit the official web registry at **[AgentTaste.dev](https://agenttaste.dev)**:

- 🌟 **Marc Lou Conversion Engine**: Founder-led copy, impulse checkout layout, 10-second proof hooks.
- 🌟 **Stripe Fluid Micro-Interactions**: Hardware-accelerated CSS physics, spring curves, zero-CLS transitions.
- 🌟 **Product Hunt #1 Launch Pack**: 60-character taglines, viral maker comments, PST launch sequencing.
- 🌟 **Stitch Minimalist Taste**: Asymmetric bento grids, breathing ambient gradients, luxury typography rhythm.
- 🌟 **Full Pro Bundle**: 50+ curated production skills with interactive Before/After diffs and instant CLI installer.

👉 **[Explore Full Registry & Pro Pass on AgentTaste.dev →](https://agenttaste.dev)**

---

## 📄 License

MIT License. Crafted with precision for the autonomous AI coding era.
