# Modul

Modul is a private Godot 4 project for a single-player Windows PC game about player-authored physical spacecraft construction. The critical MVP is: complete encounter → receive module → attach module physically → ship visibly and mechanically changes → placement creates an interaction → module may be damaged or lost in the next encounter.

## Governing Source Of Truth

[docs/MODUL_NORTH_STAR.md](docs/MODUL_NORTH_STAR.md) is the governing source of truth for the Modul project. When another document conflicts with the North Star, the North Star wins until a PO DECISION updates it.

## Core Documents

- [docs/MODUL_NORTH_STAR.md](docs/MODUL_NORTH_STAR.md) - governing product, ownership, roadmap, backlog, gates, and definitions.
- [docs/PRODUCT_CHARTER.md](docs/PRODUCT_CHARTER.md) - product purpose, audience, scope, ownership, and success measures.
- [docs/DECISION_LOG.md](docs/DECISION_LOG.md) - durable PO, design, and development decisions.
- [docs/MASTER_BACKLOG.md](docs/MASTER_BACKLOG.md) - cross-functional backlog marked by ownership and readiness.
- [docs/DESIGN_BIBLE.md](docs/DESIGN_BIBLE.md) - design rules for ship construction, modules, encounters, damage, and presentation.
- [docs/TECHNICAL_ARCHITECTURE.md](docs/TECHNICAL_ARCHITECTURE.md) - Godot 4 architecture direction, systems, data, testing, and build assumptions.
- [docs/RISK_REGISTER.md](docs/RISK_REGISTER.md) - product, design, development, and production risks.
- [docs/WORKING_MODEL.md](docs/WORKING_MODEL.md) - collaboration model between PO, ChatGPT, Codex, and playtest feedback.

## Specification Areas

- [specifications/design/README.md](specifications/design/README.md) - design specification intake and acceptance rules.
- [specifications/development/README.md](specifications/development/README.md) - development specification intake and readiness rules.

## References

- [references/REFERENCE_GAMES.md](references/REFERENCE_GAMES.md) - reference-game lessons for Pathogenic, Noita, and Pinmoney.

## Game Workspace

- [game/README.md](game/README.md) - reserved Godot 4 project area. Gameplay is intentionally not implemented in this foundation PR.

## Current Status

- PO DECISION: Modul launches from a private repository, initially targeting Windows PC.
- DESIGN — ChatGPT: Product design, design specifications, and design QA are owned by ChatGPT.
- DEVELOPMENT — Codex: Implementation, technical architecture, tests, and builds are owned by Codex.
- READY FOR CODEX: Documentation and governance foundation are ready for review.
- BLOCKED: Gameplay implementation is blocked until the North Star, design specifications, and MVP acceptance gates are approved.
