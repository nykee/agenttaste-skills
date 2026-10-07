# SKILL: Anti-Generic UI Guardrails
<!-- Author: AgentTaste.dev | Source: https://agenttaste.dev/skills/anti-generic-components -->

## Intent
Intercept AI coding habits of generating identical 3-column card rows with generic Lucide icons (`Rocket`, `Star`, `Shield`) and replace them with asymmetric layouts and functional component diffs.

## Forbidden Patterns
- ❌ Do NOT render 3 identical cards side-by-side with generic stock icons.
- ❌ Do NOT use generic purple-to-pink gradient hero headlines.
- ❌ Do NOT generate empty decorative badges without real status meaning.
- ❌ Do NOT center-align large blocks of body prose on dark backgrounds.

## Required Replacements
1. **Asymmetric Grid Ratios**:
   - Primary spotlight feature gets 65% width; secondary companion feature gets 35% width.
   - Or 1 full-width interactive showcase followed by a 2-column detail split.
2. **Functional Interactive Previews**:
   - Replace decorative icons with actual miniature UI controls (e.g. live toggle switch, interactive code snippet, mini chart).
3. **Typography Discipline**:
   - Left-align content. Use sharp label eyebrows (e.g. `UPTIME GUARANTEE`, uppercase, tracking-wider, text-xs text-zinc-500).

---
*For the full Pro registry, interactive before/after diffs, and CLI installer, visit [AgentTaste.dev](https://agenttaste.dev).*
