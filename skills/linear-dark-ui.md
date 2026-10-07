# SKILL: Linear Dark UI Standard
<!-- Author: AgentTaste.dev | Source: https://agenttaste.dev/skills/linear-dark-ui -->

## Intent
Enforce a modern, restrained, dark-first UI aesthetic inspired by Linear, Stripe, and Vercel. Completely eliminate generic bright white cards, muddy contrast, and cliché gradients.

## Core Aesthetic Principles
1. **Background Hierarchy**:
   - Canvas base: `#09090b` (Tailwind `zinc-950`).
   - Card / Panel surface: `#121215` (Tailwind `zinc-900/50` or `zinc-900`).
   - Elevated dialog / popover: `#18181b` (Tailwind `zinc-850` or `zinc-900`).
2. **Micro-Borders & Radiance**:
   - Card borders must use 1px subtle strokes: `rgba(255, 255, 255, 0.08)` or Tailwind `border-zinc-800/80`.
   - Never use thick 2px borders or high-contrast white borders.
3. **Typography & Contrast**:
   - Headings: Crisp high-contrast white (`#f4f4f5` / `zinc-100`), font tracking tighter (`tracking-tight`).
   - Body & Meta: Muted readable zinc (`#a1a1aa` / `zinc-400`).
   - Secondary / Helper: Subtle zinc (`#71717a` / `zinc-500`).
4. **Accent Colors**:
   - Accent colors (Emerald, Indigo, Violet) are surgical micro-indicators only (status dots, active tabs, subtle badges).
   - Never fill huge cards with garish gradient backgrounds.
5. **Interactive Feedback**:
   - Hover states should shift surface luminescence subtly (`zinc-900` to `zinc-800/60`), not jarring scale transforms.

---
*For the full Pro registry, interactive before/after diffs, and CLI installer, visit [AgentTaste.dev](https://agenttaste.dev).*
