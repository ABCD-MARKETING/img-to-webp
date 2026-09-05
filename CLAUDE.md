# img-to-webp — Claude Code project instructions

<!-- universal-completeness:begin (vendored from essman929/AI-MEMORY templates/universal-completeness-repo-kit — edit there, re-run install.py) -->
## Global rule: Universal Product Completeness & System Integration Protocol (2026-09-05)

**Applies to every development request in this repo, every session, every prompt.** A
request names one part of a larger system. Never change only the thing named.

Before any meaningful change run: **UNDERSTAND → LOCATE → SCAN → MAP → DESIGN →
IMPLEMENT → CONNECT → VERIFY → SEARCH AGAIN → AUDIT → REPORT.**

- **Four levels, never stop at 1:** User goal → full Workflow → System (pages, DB,
  APIs, automations, permissions, AI, notifications, reports) → Architecture.
- **Scan the whole repo first** (grep references, imports, schema, queries,
  endpoints, consumers, webhooks, jobs, prompts, agents, config, env, permissions,
  analytics, notifications, docs, tests, flags). Inspect DB schema and API
  contracts when available. Search again after building.
- **Change Impact Map** across frontend · backend · database · APIs · automations ·
  AI · business logic · analytics · security · tests.
- **Classify gaps P0 / P1 / P2.** Build P0 + safe P1. No speculative P2.
- **Connect every layer:** UI → API → backend → DB → result → UI; automations,
  AI prompts/agents, permissions (enforced on the backend), analytics, integrations.
- **Complete the entity:** CRUD + states (loading/empty/error/…) + forms +
  tables + permissions + cross-module links, sized to what the entity needs.
- **Single source of truth** over duplicated logic/config. Search before any
  rename/remove. Name architectural problems instead of building on them.
- **Done = user can operate the full workflow end to end**, verified with the
  repo's own checks and a real user-flow test. Visual ≠ functional.
- **Report:** changed · connected · dependencies found · extras · intentionally
  skipped · risks · P2 recs · workflow verified?

Operating copy: `.claude/skills/universal-completeness/SKILL.md`. Canonical text
(43 sections): `essman929/AI-MEMORY` → `memory/UNIVERSAL-COMPLETENESS-PROTOCOL.md`.
Per-prompt reminder: `.claude/hooks/universal-completeness.sh` (UserPromptSubmit).
Repo-specific rules above win on conventions (branch, deploy, DB access); this
protocol wins on completeness.
<!-- universal-completeness:end -->
