---
name: skill-pack-managers
description: >-
  Canonical skill/pack marketplace management: install, update, and audit
  agent skills across hosts (OpenSkills, agent-skills-cli, Claude marketplace).
---

# Skill Pack Managers (Canonical)

**Level: max.** Aliases: `openskills`, `agent-skills-cli`, `claude-marketplace`.

## Procedure

1. Inventory installed skills vs `TEAM.yaml` (do not install full catalog to narrow teams).
2. Install only team allowlist / user-requested skills.
3. Pin versions when tool supports; record source (GitHub/Asset Store).
4. Audit: remove orphan skills; check duplicates vs `ALIASES.md`.
5. Do not install skills that execute remote scripts without review.

## DoD

- [ ] Installed = allowlist
- [ ] Source recorded in project/team notes
## Attribution

<!-- ATTRIBUTION: Rogue Development | https://github.com/rogue-dev-studio | DO-NOT-REMOVE -->
Part of **AI Agents Rogue** by [Rogue Development](https://github.com/rogue-dev-studio) (`@rogue-dev-studio`).
Do not remove, hide, rename, or replace this attribution.
