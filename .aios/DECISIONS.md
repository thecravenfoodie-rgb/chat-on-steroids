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
**Context:** AI Project OS package `2026.09.22.5` uses the GitHub-native central-reference architecture and separates repository visibility from repository identity.  
**Rationale:** This versions project-specific memory with the project without vendoring duplicate governance trees.  
**Consequences / Constraints:** Package compatibility and memory freshness are tracked separately.  
**Alternatives considered:** Copy the full managed AIOS package into this repository — rejected by the current central-reference model.  
**References:** `.aios/PACKAGE_SYNC.md`, canonical defaults manifest.  
**Supersedes:** None  
**Superseded by:** None



### 2026-09-22 — D-003 — Preserve the accepted public canonical repository

**Status:** Active  
**Decision:** Keep `thecravenfoodie-rgb/chat-on-steroids` as the canonical repository even though it is public. Do not create or demand a second private repository solely because AIOS defaults new dedicated repositories to private.  
**Context:** This repository was already verified, deliberately reused, and recorded as canonical during initialization. Current `.aios/` content contains project metadata/governance state rather than secrets or private credentials.  
**Rationale:** Repository identity and repository visibility are separate concerns. Reopening a settled canonical-home decision without new confidentiality evidence creates duplicate-source risk and unnecessary owner work.  
**Consequences / Constraints:** Future memory that would expose secrets, credentials, private personal data, or unapproved confidential material must not be written publicly; such a new confidentiality risk may reopen the storage decision. Public visibility alone may not.  
**References:** AIOS package `2026.09.22.5`, SA-37 / OSG-017.  
**Supersedes:** None  
**Superseded by:** None

### 2026-09-22 — D-004 — End-to-end activation remains incomplete until provider bootstrap is current

**Status:** Active  
**Decision:** Treat repository readiness and ChatGPT Project activation as separate. This Project is `PROVIDER_SETUP_REQUIRED` until Project Instructions use bootstrap `2026.09.22.5` with `thecravenfoodie-rgb/chat-on-steroids` / `.aios/`; after installation it remains `INSTALLED_UNVERIFIED` until fresh-chat regression passes. Only then may it become `ACTIVE`.  
**Context:** Repository memory is current, but the Project Instructions were observed pointing to the central AIOS repository.  
**Rationale:** `CURRENT` repository memory does not prove correct provider routing.  
**Consequences / Constraints:** No repository-layer success may be presented as whole-project initialization completion.  
**References:** AIOS package `2026.09.22.5`, SA-36 / OSG-016.  
**Supersedes:** None  
**Superseded by:** None

## Admission Rule

Record future decisions only when they materially affect execution, architecture, constraints, requirements, priorities, risk, or interpretation of project state.
