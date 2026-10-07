# SKILL: Claude Code Clean Architecture (Lite)
<!-- Author: AgentTaste.dev | Source: https://agenttaste.dev/skills/claude-code-clean-arch -->

## Intent
Prevent autonomous coding agents from generating 800-line monolithic spaghetti files, mixing database queries directly into React components, or creating unmaintainable code structures.

## Architectural Constraints
1. **File Size Hard Ceiling**:
   - Any single component or route exceeding 250 lines must be decomposed into dedicated submodules.
2. **Layer Separation**:
   - UI components must strictly handle presentation and local UI state.
   - Database queries and external mutations must live in server-only service modules (`.server.ts` or `services/`).
3. **Zod Contracts**:
   - Every external payload, API response, and form submission must be validated with an explicit Zod schema.
4. **Error Handling**:
   - Avoid silent swallows (`catch (e) {}`). All failure paths must produce deterministic error types or toast notifications.

---
*For the full Pro registry, interactive before/after diffs, and CLI installer, visit [AgentTaste.dev](https://agenttaste.dev).*
