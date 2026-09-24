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



### 2026-09-22 — D-005 — Build the fork; do not substitute stock CoS installation

**Status:** Active  
**Decision:** This project's objective is to modify `thecravenfoodie-rgb/chat-on-steroids` into the AIOS execution/control layer. Installing or configuring the unmodified upstream Chat On Steroids release is not the project deliverable and must not replace source implementation.  
**Context:** A work session drifted into downloading the upstream macOS release after reading project memory that overemphasized provider/setup state. The owner explicitly redirected the work back to building the fork.  
**Rationale:** The fork exists to become an AIOS execution layer; stock installation tests a different objective.  
**Consequences / Constraints:** Use installation/runtime setup only when genuinely needed to verify the modified build. Normal continuation begins from source/branch/worktree state and the Phase 1 implementation handoff.  
**References:** `.aios/PROJECT.md`, `.aios/STATE.md`, branch `aios/phase-1-core-integration`.  
**Supersedes:** None  
**Superseded by:** None

### 2026-09-22 — D-006 — Phase 1 is Core-first and provider regression is non-blocking

**Status:** Active  
**Decision:** Continue Phase 1 as a Core-first implementation of the AIOS execution layer. Provider/bootstrap fresh-chat regression remains truthful but deferred and must not block product implementation.  
**Context:** The project needs forward implementation progress now; provider regression can be completed later without falsifying its status.  
**Rationale:** Provider verification is lifecycle maintenance, not a dependency for editing/testing the fork's source.  
**Consequences / Constraints:** Prioritize the Core execution path, identity/ownership protection, execution receipts, worker handoff/resume, and lifecycle/control integration. Broader Desktop/Plugins expansion stays outside the immediate Phase 1 path unless a concrete implementation dependency requires it. Do not mark provider verification complete without evidence.  
**References:** `.aios/STATE.md`, `.aios/MEMORY_SYNC.md`.  
**Supersedes:** None  
**Superseded by:** None


### 2026-09-24 — D-007 — Use Sidecar as the visible product brand while preserving compatibility identities

**Status:** Active  
**Decision:** Rename the visible product to **Sidecar** and publish its model-facing connectors as **Sidecar Core**, **Sidecar Desktop**, and **Sidecar Plugins**. Preserve the existing repository/package slug, app id, MCP server ids, browser wire id, storage/userData keys, and native/internal `cos` identifiers unless a later migration provides an explicit compatibility path.  
**Context:** The owner no longer wants the product associated by name with ChatGPT or “steroids.” A visible-only rename can remove that association without orphaning settings, permissions, stored state, historical conversations, or transport identities.  
**Rationale:** Branding and compatibility identity are separate concerns. Renaming user-visible surfaces now delivers the desired product identity while avoiding unnecessary breakage in mature internal contracts.  
**Consequences / Constraints:** Existing conversations continue to recognize the prior connector display names as transitional read compatibility, but new publication uses Sidecar names. Future release artifacts use `Sidecar-*`. Update/release lookup targets the canonical fork and must not fall back to upstream Chat On Steroids releases. Original copyright attribution remains intact where legally relevant. A deeper rename of technical identifiers requires its own migration plan and is not implied by the brand change.  
**References:** local worktree on `aios/phase-1-core-integration`; `docs/worklog-2026-09-24-sidecar-brand-migration.md`.  
**Supersedes:** None  
**Superseded by:** None

## Admission Rule

Record future decisions only when they materially affect execution, architecture, constraints, requirements, priorities, risk, or interpretation of project state.
