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

---

<!-- product-design-system:begin (vendored from essman929/AI-MEMORY templates/universal-completeness-repo-kit — edit there, re-run install.py) -->
## Global rule: Premium Product Design, UI/UX, Graphics & System Completeness (2026-09-17)

**Applies whenever this repo's UI, pages, branding, graphics or user experience are
built, modified, redesigned, improved, fixed or continued — every session, every prompt.**
Act as CPO + CDO + UX architect + brand designer + design-systems engineer. Target the
Stripe / Linear / HubSpot / Salesforce / Meta Business Suite bar (never copy them). No
generic template-looking output. **Functional ≠ complete** until design, branding,
responsiveness, states and workflows are complete too.

- **Scott is not a designer.** "Make it sharp / professional / modern / better / like a
  million-dollar system" = a full product-design pass. Make defensible design decisions
  and proceed; ask only what affects brand, business rules, architecture or UX.
- **Discover first:** stack, existing design system, tokens, components, brand/logo
  files, palette in this file, routes, auth, schema. Extend what exists; never replace
  approved branding or rewrite working backend for a look.
- **Design direction before major UI code:** coherent palette, type hierarchy, spacing,
  radius, shadows, component heights as centralized tokens (Tailwind/shadcn/Radix/
  Lucide/Inter when compatible). Light corporate often beats dark-tech. No auto dark
  mode, glassmorphism, gradient piles, neon, placeholder logos or mock-looking graphics.
- **Every page:** purpose, primary user, primary action, hierarchy, states (loading,
  empty with CTA, error, success, unauthorized), mobile behaviour, permissions.
- **Responsive for real:** 320 / 375 / 390 / 430 / tablet / laptop / desktop / wide —
  redesign layout behaviour, don't shrink desktop.
- **Whole-app consistency:** one page polished next to unchanged pages is a defect.
  Shared tokens + components across the application.
- **Quality gate before "done":** design system · typography · colours · spacing ·
  components · graphics · responsive · accessible · loading/empty/error/success ·
  complete workflows · DB/API/auth wired · no placeholder content · tests · project
  still works. Then the Forensic QA gate.

Operating copy: `.claude/skills/global-product-design-system/SKILL.md`. Canonical text
(17 sections): `essman929/AI-MEMORY` → `memory/GLOBAL-PRODUCT-DESIGN-SYSTEM.md`.
Repo-specific rules above win on stack, branch, deploy and approved palette; this rule
wins on design quality. Pairs with the Universal Completeness Protocol (what must be
connected) and the Forensic QA Protocol (final audit).
<!-- product-design-system:end -->
