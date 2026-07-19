# Development Specifications

This folder holds implementation-facing specifications owned by Codex.

## Ownership

- DEVELOPMENT — Codex: Owns technical design, implementation plans, tests, builds, and engineering QA.
- DESIGN — ChatGPT: Provides design intent and player-facing acceptance criteria for game features.
- PO DECISION: Resolves scope and priority questions.

## Required Specification Shape

Each development specification should include:

- Status marker: DEVELOPMENT — Codex, READY FOR CODEX, or BLOCKED.
- Source design specification or PO decision.
- Technical approach.
- Data model or scene structure.
- Tests and validation.
- Build or platform impact.
- Risks and rollback notes.

## Initial Needed Specs

- READY FOR CODEX: Godot 4 scaffold specification.
- BLOCKED: Ship construction architecture until attachment rules are approved.
- BLOCKED: Module data model until module taxonomy is approved.
- BLOCKED: Encounter loop implementation until MVP encounter design is approved.
- BLOCKED: Damage and loss implementation until damage rules are approved.

## Ready Rule

READY FOR CODEX means the implementation scope is narrow, testable, and aligned with the North Star.
