# Guidance for Coding Agents

This repository is the early-stage, source-available home of **Demble**.

## Product intent

Demble is a self-hostable collaboration workspace for small human teams and their coding agents. Humans own decisions; AI may propose changes, but proposals require explicit human review before becoming confirmed project state.

Read `README.md`, `README.zh-CN.md`, and `docs/ROADMAP.md` before making architectural assumptions.

## Constraints

- **Do not assume a specific coding-agent harness.** The project intends to support different coding tools through stable interfaces.
- **Do not introduce a required external IM or meeting service** for the core user workflow without an approved product decision.
- **Do not claim unimplemented features are shipped.** Mark proposals, prototypes, and production behavior clearly.
- **Do not silently promote inferred AI content to authoritative decisions, plans, or assignments.** Include explicit review boundaries.
- **Do not access, upload, or replicate private chats, agent sessions, credentials, or local files** without user consent and an authorized scope.
- **Prefer the smallest verifiable end-to-end slice.** Make assumptions visible and document reversibility.
- **Preserve source traceability.** Changes to shared context must retain origin and revision information.

## Working on tasks

1. Confirm the intended user scenario and the current roadmap slice.
2. State assumptions when the product or technical contract is undecided.
3. Implement only the authorized scope; use tests and reproducible verification where possible.
4. Report what changed, what was tested, what remains uncertain, and any permission or security risks.

No tool-specific instructions are required. Keep this file compatible with Codex, Claude Code, OpenCode, and other coding agents.
