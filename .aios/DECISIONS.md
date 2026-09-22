# DECISIONS

**Project:** AIOS Execution Layer • Chat On Steroids • Sept 22

## Active / Historical Decisions

### 2026-09-22 — D-001 — Reuse the verified existing Chat On Steroids repository

**Status:** Active  
**Decision:** Use `thecravenfoodie-rgb/chat-on-steroids` as this ChatGPT Project's canonical repository and place AI Project OS memory under `.aios/`.  
**Context:** The Project name includes Chat On Steroids, and the authorized repository README/package metadata independently identify the same product.  
**Rationale:** A verified matching repository already exists; creating another repository would split source and project memory.  
**Consequences / Constraints:** All AIOS writes for this Project are locked to `thecravenfoodie-rgb/chat-on-steroids`. The central `thecravenfoodie-rgb/ai-project-os` repository remains governance source only. The existing public visibility is preserved rather than silently renamed or duplicated.  
**Alternatives considered:** Create a new private repository from the Project name — rejected because a verified matching repository already exists.  
**References:** repository README, `package.json`, canonical existing-repository initializer.  
**Supersedes:** None  
**Superseded by:** None

### 2026-09-22 — D-002 — Use GitHub-native AIOS memory under .aios

**Status:** Active  
**Decision:** Canonical project memory lives at `thecravenfoodie-rgb/chat-on-steroids/.aios/`; reusable AIOS governance remains centralized in `thecravenfoodie-rgb/ai-project-os`.  
**Context:** AI Project OS package `2026.09.22.4` uses the GitHub-native central-reference architecture.  
**Rationale:** This versions project-specific memory with the project without vendoring duplicate governance trees.  
**Consequences / Constraints:** Package compatibility and memory freshness are tracked separately.  
**Alternatives considered:** Copy the full managed AIOS package into this repository — rejected by the current central-reference model.  
**References:** `.aios/PACKAGE_SYNC.md`, canonical defaults manifest.  
**Supersedes:** None  
**Superseded by:** None

## Admission Rule

Record future decisions only when they materially affect execution, architecture, constraints, requirements, priorities, risk, or interpretation of project state.
