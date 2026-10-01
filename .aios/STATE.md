# STATE

**Updated:** 2026-10-01 America/New_York

## Goal

Reconcile the canonical Chat On Steroids repository with upstream 2.1.23, preserve intentional project work, then build a fresh installation from the approved canonical source. This maintenance does not complete the underlying Phase 1 AIOS execution-layer implementation.

## Current Truth

- Canonical repository: `thecravenfoodie-rgb/chat-on-steroids`; existing public visibility remains intentionally accepted.
- Canonical project-memory path: `main:.aios/`; AIOS package remains `2026.09.22.5`.
- Publication baseline: `e63c4f726d857ca99df78789b93fb87b63df3bfa` on canonical `main`, declaring 2.1.14.
- Pinned upstream 2.1.23 baseline: `26d46e0207674a6bbdad864b17787b3538f60492`.
- All 12 canonical project records are retained in the local reconciliation candidate.
- The upstream merge completed locally without conflicts. Product code matches the pinned upstream baseline; the retained Phase 1 Core terminal/Git regression is adapted to the current command contract.
- Candidate branch: `reconcile/upstream-2.1.23-clean-reset`. It is local and unpublished; canonical `main` has not been updated.
- Original local source trees remain intact. Their Git histories and tracked diffs have verified private preservation copies; unique untracked material remains untouched at its original locations.
- Uncommitted acceptance receipt/attribution fixes are preserved separately and excluded from the candidate, as directed by the owner.
- Visible brand remains Chat On Steroids with Core/Desktop/Plugins connector names; the Sidecar rename remains superseded by D-008.
- Compatibility identifiers remain unchanged: package/repository slug, app id, MCP server ids, browser wire identity, storage keys, and native `cos` identifiers.
- The current installed application and working Core registration remain unchanged.
- Provider/bootstrap activation remains unverified, deferred, and separate from this maintenance.

## Active Work

Clean-reset reconciliation and local verification, followed by the explicit owner approval gates in D-009. The underlying Phase 1 implementation branch remains `aios/phase-1-core-integration`.

## Preservation and Approval Boundaries

- Selectively preserve user files, skills, archived history, attachments, and unique local work; do not import old runtime ledgers, secrets, pairing, or queued work into the fresh installation.
- Build and validate the candidate before presenting the exact reconciliation diff for source-publication approval. No push or canonical-main update before that approval.
- Obtain separate approval before replacing the installed app or resetting its data/preferences.
- Keep the working Core registration until the fresh canonical-built runtime passes local build, installation, startup, and local verification; obtain exact-registration cutover approval afterward.
- Permanently delete no quarantined repository, acceptance environment, installer, app-data backup, or rollback snapshot until full acceptance, including CoS restart and post-restart Core attribution, passes and final cleanup is approved.

## Pending Verification

- Candidate full verification, UI checks, ARM64 packaging, and packaged-runtime/bundle checks.
- Source-publication approval and independent remote commit verification.
- Installation, startup, fresh Core cutover, end-to-end acceptance, restart attribution, and pink theme persistence.
- Phase 1 implementation and provider/bootstrap regression remain unfinished; no completion claim is made for either.

## Next Executable Action

Finish candidate validation, record exact results, and present the reconciliation diff and candidate identity at the source-publication approval gate. Stop on a substantive verification failure; do not resume speculative recovery patching.
