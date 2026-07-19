# Working Model

## Collaboration Model

Modul uses explicit ownership boundaries so product direction, design quality, and implementation quality can move together without blurring accountability.

## Roles

- PO DECISION: The product owner decides scope, priority, unresolved tradeoffs, release gates, and GTM direction.
- DESIGN — ChatGPT: ChatGPT owns product design, design specifications, design QA, reference interpretation, player-facing acceptance criteria, and playtest synthesis.
- DEVELOPMENT — Codex: Codex owns implementation, technical architecture, tests, builds, engineering QA, and technical handoff.

## Work Intake

1. PO DECISION: A priority or question is identified.
2. DESIGN — ChatGPT: Design intent and acceptance criteria are drafted when player-facing behavior is involved.
3. DEVELOPMENT — Codex: Technical approach, dependencies, and test strategy are identified.
4. READY FOR CODEX: Work is implemented only after scope, design intent, and acceptance criteria are clear.
5. BLOCKED: Work waits when direction, acceptance, or dependencies are unresolved.

## Issue Workflow

- Feature issues capture player value, design intent, and technical acceptance.
- Bug issues capture observed behavior, expected behavior, reproduction, and severity.
- Design-task issues capture design questions, references, and required outputs.
- Technical-debt issues capture technical risk, affected systems, and payoff.
- Playtest-finding issues capture observed player behavior, interpretation, and proposed follow-up.

## PR Workflow

- DEVELOPMENT — Codex: PRs should state what changed, why, validation performed, and design QA needs.
- DESIGN — ChatGPT: Player-facing PRs require design QA notes or a clear reason QA is not applicable.
- PO DECISION: Scope changes discovered during implementation must be logged.

## Handoff Rules

- READY FOR CODEX: A work item has clear acceptance criteria, dependencies, and owner.
- BLOCKED: A work item is blocked when it needs a PO decision, design spec, asset direction, technical dependency, or stage-gate approval.
- DEVELOPMENT — Codex: Implementation handoff should include tests run and known limitations.
- DESIGN — ChatGPT: Design handoff should include player-facing intent and QA questions.

## Documentation Rules

- [MODUL_NORTH_STAR.md](MODUL_NORTH_STAR.md) governs.
- Decision changes go in [DECISION_LOG.md](DECISION_LOG.md).
- Backlog changes go in [MASTER_BACKLOG.md](MASTER_BACKLOG.md).
- Risks go in [RISK_REGISTER.md](RISK_REGISTER.md).
- Design rules go in [DESIGN_BIBLE.md](DESIGN_BIBLE.md).
- Technical rules go in [TECHNICAL_ARCHITECTURE.md](TECHNICAL_ARCHITECTURE.md).
