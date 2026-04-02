## Welcome to DevForgeAtlas — Member Overview

This view is visible to org members only. Here is everything you need to get oriented and productive.

---

## Current State

| | |
|---|---|
| **Active version** | v1.6.2 |
| **Current phase** | Phase 8 — E2E Testing (last gate before npm publish) |
| **Next milestone** | `npm publish @devforgeatlas/devforge-atlas` after E2E passes |
| **Pending** | Brian's incoming skill files (CPO, Tech Writer, Sales Pitch, Marketing Manager) → v1.7.0 |

---

## Repositories

| Repo | What It Is |
|------|------------|
| [DevForge-Atlas](https://github.com/DevForgeAtlas-Org/DevForge-Atlas) | 🔒 Main monorepo — plugin, global brain, VS Code extension, standalone generator. All active development lives here. |
| [DevForge-Carta](https://github.com/DevForgeAtlas-Org/DevForge-Carta) | 🌐 Auto-published standalone files. Syncs from Atlas on every GitHub Release via `publish-carta.yml`. |
| [DevForge-Templates](https://github.com/DevForgeAtlas-Org/DevForge-Templates) | 🌐 Curated project starter templates. Accessible via `//template` in the plugin. |
| [DevForge-GateKeeper](https://github.com/DevForgeAtlas-Org/DevForge-GateKeeper) | 🔒 Auth and access management. |

---

## Getting Started on DevForge-Atlas

1. Clone `DevForge-Atlas` and open it in Claude Code
2. Run `//catch-up` — DevForge reads all docs and presents current state
3. Check `devforge/CONTEXT.md` for the active task and next priority
4. Check `devforge/ROADMAP.md` for phase status and what to build next

**Key docs inside Atlas:**
- `devforge/CONTEXT.md` — current state, active task, session notes
- `devforge/ROADMAP.md` — every phase, every task, definitions of done
- `devforge/ARCHITECTURE.md` — system design and layer rules
- `devforge/DECISIONS.md` — why things are the way they are (read before proposing changes)
- `devforge/BUGS.md` — open Critical and High issues
- `devforge/CHANGELOG.md` — full version history

---

## How We Work

- **Branching:** Feature branches off `main`. Conventional commits (`feat:`, `fix:`, `docs:`, `security:`).
- **Shipping:** Every release gets a GitHub Release tag → triggers Carta auto-publish automatically.
- **Docs:** Updated as part of every task — not after. CONTEXT.md is the project memory.
- **Brain:** Global brain lives at `~/.devforge/`. Never committed to any repo.
- **Approval gates:** All learning proposals and behaviour changes require explicit human sign-off. No silent changes.

---

## Four Delivery Mechanisms

| | |
|---|---|
| **Standalone CLAUDE.md** | Drop `DEVFORGE_v5.md` as `CLAUDE.md` — zero install, works immediately. Published via Carta. |
| **Claude Code Plugin** | `npm install -g @devforgeatlas/devforge-atlas` — full brain, 11 agents, 87 commands. |
| **VS Code Extension** | Visual sidebar + brain dashboard. In development. |
| **Multi-platform configs** | GPT, Copilot, Cursor, Windsurf — same intelligence, native format. |

All four must work independently of each other. This is a hard rule.

---

*Maintainers: [@cyberspartan77](https://github.com/cyberspartan77) + [@netsecops-76](https://github.com/netsecops-76)*