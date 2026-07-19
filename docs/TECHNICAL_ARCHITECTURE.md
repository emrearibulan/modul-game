# Technical Architecture

## Authority

This document translates the North Star into technical direction for Codex. If it conflicts with [MODUL_NORTH_STAR.md](MODUL_NORTH_STAR.md), the North Star wins.

## Baseline

- PO DECISION: Engine is Godot 4.
- PO DECISION: Initial platform is Windows PC.
- PO DECISION: Repository is private.
- PO DECISION: Initial launch scope is single-player.
- DEVELOPMENT — Codex: Implementation, architecture, testing, and builds are Codex-owned.

## Architecture Principles

- DEVELOPMENT — Codex: Build MVP systems before broad frameworks.
- DEVELOPMENT — Codex: Keep module behavior data-driven where it reduces iteration cost.
- DEVELOPMENT — Codex: Make systemic interactions testable outside manual play wherever practical.
- DEVELOPMENT — Codex: Separate design-authored module definitions from scene glue.
- DEVELOPMENT — Codex: Prefer deterministic, inspectable behavior for placement, damage, and routing rules.

## Proposed Godot Project Shape

The `game/` folder is reserved for the Godot 4 project. It is intentionally a placeholder until the scaffold task is approved.

Expected future structure:

```text
game/
  project.godot
  scenes/
  scripts/
  resources/
  tests/
  tools/
```

## Core Systems To Design For

- DEVELOPMENT — Codex: Ship body representation.
- DEVELOPMENT — Codex: Attachment points or construction grid.
- DEVELOPMENT — Codex: Module definitions and instances.
- DEVELOPMENT — Codex: Visible module state changes.
- DEVELOPMENT — Codex: Mechanical stat or capability changes.
- DEVELOPMENT — Codex: Encounter state machine.
- DEVELOPMENT — Codex: Reward and inventory handoff.
- DEVELOPMENT — Codex: Damage, disable, sever, and loss model.
- BLOCKED: Power routing implementation until rules are specified.
- BLOCKED: Exposure calculations until camera, collision, and ship geometry decisions are made.

## Data Direction

READY FOR CODEX after design approval:

- Module definitions should include identity, visual resource, footprint, sockets, orientation rules, mechanical effects, damage states, and tags.
- Encounter definitions should include objective, hazard/enemy setup, reward rules, failure state, and test fixtures.
- Ship state should serialize enough information to rebuild attached modules, orientation, damage state, and mechanical effects.

## Testing Direction

- DEVELOPMENT — Codex: Unit tests for pure module and ship state rules.
- DEVELOPMENT — Codex: Integration tests for attachment, detachment, damage, and reward flow.
- DEVELOPMENT — Codex: Scene smoke tests for MVP loop entry points.
- DEVELOPMENT — Codex: Windows build verification before playtest handoff.
- DESIGN — ChatGPT: Design QA validates clarity, feel, and player-facing acceptance criteria.

## Build Direction

- DEVELOPMENT — Codex: Windows PC is the initial build target.
- DEVELOPMENT — Codex: Build scripts should be repeatable locally first, then suitable for CI.
- BLOCKED: CI provider and artifact retention policy.

## Technical Risks

- BLOCKED: Spatial construction can become expensive if the representation is chosen before design rules are stable.
- BLOCKED: Systemic interactions can become untestable if authored only as scene scripts.
- BLOCKED: Visual ship changes can conflict with gameplay collision if art and mechanics are not separated carefully.
