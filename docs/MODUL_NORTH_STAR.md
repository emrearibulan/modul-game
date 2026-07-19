# Modul North Star

## Document Authority

This document is the governing source of truth for Modul. It has authority over the product charter, design bible, technical architecture, backlog, issue templates, and sprint plans unless a later PO DECISION updates this document.

- PO DECISION: The project is private, uses Godot 4, targets Windows PC first, and launches as a single-player game.
- DESIGN — ChatGPT: ChatGPT owns product design, design specifications, and design QA.
- DEVELOPMENT — Codex: Codex owns implementation, technical architecture, testing, and builds.
- READY FOR CODEX: Codex may implement only work that has a clear owner, acceptance criteria, and current alignment with this North Star.
- BLOCKED: Gameplay implementation is blocked until the initial MVP specifications are approved.

## Product Vision

Modul is a systemic spacecraft construction game where the player's ship is not a menu of stats but a physical, visible, vulnerable object assembled from found and earned parts. The player survives by expanding, rerouting, shielding, sacrificing, and experimenting with modules that change both the silhouette and behavior of the ship.

## Player Fantasy

The player fantasy is to be a hands-on spacecraft survivor-engineer. The player should feel that every bolted-on choice matters: a weapon jutting from one side changes firing arcs, a reactor placed deep inside changes survivability, exposed systems invite tactical risk, and a damaged module changes the story of the ship.

## Design Pillars

1. DESIGN — ChatGPT: Physical construction is the core interface.
   Modules must occupy space, attach to the ship, and visibly alter the craft.

2. DESIGN — ChatGPT: Placement creates consequences.
   Placement, orientation, power routing, adjacency, and exposure should eventually affect behavior.

3. DESIGN — ChatGPT: Damage is a design language.
   Modules may be damaged, disabled, severed, or lost. The ship should carry battle history forward.

4. DESIGN — ChatGPT: Systemic interactions beat scripted novelty.
   Modules should combine in readable ways so players discover strategies through experimentation.

5. DEVELOPMENT — Codex: Build the smallest complete loop first.
   The MVP must prove the encounter-to-module-to-ship-change-to-risk loop before expanding content.

## Reference-Game Lessons

### Pathogenic

- DESIGN — ChatGPT: Use Pathogenic as the reference for visible physical progression and spatial component synergies.
- SHOULD COPY: The clarity that new pieces physically reshape the player's capability graph.
- SHOULD NOT COPY: Any surface fiction, pacing, or system wholesale if it weakens Modul's spacecraft identity.

### Noita

- DESIGN — ChatGPT: Use Noita as a reference for systemic interaction and player experimentation.
- SHOULD COPY: The joy of combining parts into surprising outcomes.
- SHOULD NOT COPY: Full pixel simulation, uncontrolled combinatorial scope, or unreadable chaos.

### Pinmoney

- DESIGN — ChatGPT: Use Pinmoney as the graphical polish reference.
- SHOULD COPY: Crisp presentation, tactile feedback, and a polished visual finish.
- SHOULD NOT COPY: Gameplay structure, economy assumptions, or progression model.

## What Modul Should Copy

- DESIGN — ChatGPT: Physical readability from Pathogenic.
- DESIGN — ChatGPT: Experiment-driven combinations from Noita.
- DESIGN — ChatGPT: Visual polish ambition from Pinmoney.
- DEVELOPMENT — Codex: Technical discipline that keeps systemic behavior testable and debuggable.

## What Modul Should Not Copy

- DESIGN — ChatGPT: Modul should not become a pure stat-sheet builder.
- DESIGN — ChatGPT: Modul should not copy Noita's full material simulation.
- DESIGN — ChatGPT: Modul should not use Pinmoney as a gameplay reference.
- DEVELOPMENT — Codex: Modul should not build broad engine abstractions before the MVP proves the loop.

## Product Positioning

Modul is positioned as a single-player systemic construction game for players who enjoy building, experimenting, adapting to loss, and reading physical consequences. Its differentiator is player-authored physical spacecraft construction where every major module changes the ship's visible form and practical behavior.

## Ownership Model

- PO DECISION: Product owner decisions set scope, priority, release gates, and unresolved tradeoffs.
- DESIGN — ChatGPT: Owns product design, design specifications, design QA, reference interpretation, player fantasy, and acceptance criteria for feel.
- DEVELOPMENT — Codex: Owns Godot 4 implementation, technical architecture, tests, performance, builds, and engineering QA.
- READY FOR CODEX: Work enters implementation only when it has an approved design outcome and testable acceptance criteria.
- BLOCKED: Work with unresolved product direction, missing acceptance criteria, or contradictory references stays out of implementation.

## Zero-To-GTM Roadmap

### Phase 0: Foundation

- READY FOR CODEX: Establish documents, governance, issue templates, PR workflow, and ownership boundaries.
- DESIGN — ChatGPT: Define the MVP loop and design acceptance language.
- DEVELOPMENT — Codex: Define technical architecture and Godot project setup criteria.

### Phase 1: Critical MVP Prototype

- DESIGN — ChatGPT: Specify one encounter, one reward flow, one attachment flow, and a small module set.
- DEVELOPMENT — Codex: Implement the smallest playable loop with visible ship alteration and module damage/loss.

### Phase 2: Systems Proof

- DESIGN — ChatGPT: Add placement, orientation, power routing, exposure, and interaction rules.
- DEVELOPMENT — Codex: Build data-driven module definitions, test harnesses, and deterministic encounter validation.

### Phase 3: Content Slice

- DESIGN — ChatGPT: Expand module families, encounter types, progression beats, and visual feedback.
- DEVELOPMENT — Codex: Build content pipelines, save/load, telemetry hooks, and Windows builds.

### Phase 4: Private Playtest

- DESIGN — ChatGPT: Run design QA against player comprehension, experimentation, and attachment behavior.
- DEVELOPMENT — Codex: Stabilize builds, collect defects, and measure performance.

### Phase 5: GTM Readiness

- PO DECISION: Decide store strategy, public positioning, launch date, pricing, and trailer/key art needs.
- DESIGN — ChatGPT: Validate pitch, screenshots, onboarding, and store-page claims.
- DEVELOPMENT — Codex: Produce release candidate builds and deployment checklist.

## Stage Gates

1. Foundation Gate
   - READY FOR CODEX: Core documents exist, ownership is explicit, and issue templates support the workflow.

2. MVP Design Gate
   - DESIGN — ChatGPT: MVP module, encounter, attachment, damage, and interaction specs are approved.
   - BLOCKED: Implementation does not begin without acceptance criteria.

3. MVP Playability Gate
   - DEVELOPMENT — Codex: The critical MVP loop is playable end to end in Godot 4 on Windows PC.

4. Systems Gate
   - DESIGN — ChatGPT: Placement, orientation, power routing, and exposure create readable player decisions.
   - DEVELOPMENT — Codex: Systems are testable, data-driven, and performant.

5. Content Slice Gate
   - DESIGN — ChatGPT: Content supports experimentation without losing clarity.
   - DEVELOPMENT — Codex: Content tools and builds support repeatable iteration.

6. Playtest Gate
   - PO DECISION: Decide whether feedback supports continued scope, pivot, or reduction.

7. GTM Gate
   - PO DECISION: Approve public-facing positioning, release path, and launch readiness.

## Feature-Level Backlog

- READY FOR CODEX: Repository documentation and governance foundation.
- DESIGN — ChatGPT: MVP encounter design specification.
- DESIGN — ChatGPT: MVP module taxonomy and attachment rules.
- DESIGN — ChatGPT: Ship readability and visual-change specification.
- DEVELOPMENT — Codex: Godot 4 project scaffold under `game/`.
- DEVELOPMENT — Codex: Module data model and attachment validation.
- DEVELOPMENT — Codex: Encounter prototype loop.
- DEVELOPMENT — Codex: Damage, disable, sever, and loss prototype.
- DEVELOPMENT — Codex: Windows PC build pipeline.
- BLOCKED: Power routing implementation until design rules are approved.
- BLOCKED: Orientation-specific gameplay until MVP attachment controls are specified.
- BLOCKED: Content expansion until the critical MVP loop is validated.

## First Six Sprints

### Sprint 1: Foundation And Project Shape

- READY FOR CODEX: Create documentation foundation, issue templates, and PR template.
- DEVELOPMENT — Codex: Prepare Godot project scaffold criteria.
- DESIGN — ChatGPT: Draft MVP design specification outline.

### Sprint 2: MVP Design Lock

- DESIGN — ChatGPT: Define one encounter, module reward, attachment interaction, and damage/loss rule.
- PO DECISION: Approve the MVP scope.
- BLOCKED: Code remains blocked until approval.

### Sprint 3: Godot Scaffold And Ship Core

- DEVELOPMENT — Codex: Create Godot 4 project scaffold.
- DEVELOPMENT — Codex: Implement ship body representation and attachment points.
- DESIGN — ChatGPT: Validate ship readability.

### Sprint 4: Module Attachment Loop

- DEVELOPMENT — Codex: Implement module acquisition and physical attachment.
- DEVELOPMENT — Codex: Make modules visibly and mechanically alter the ship.
- DESIGN — ChatGPT: QA attachment clarity and feedback.

### Sprint 5: Encounter And Damage Loop

- DEVELOPMENT — Codex: Implement one complete encounter and module damage/loss.
- DESIGN — ChatGPT: QA whether damage feels readable, fair, and consequential.

### Sprint 6: MVP Validation

- DEVELOPMENT — Codex: Stabilize Windows PC build and smoke tests.
- DESIGN — ChatGPT: Run MVP design QA and prepare playtest questions.
- PO DECISION: Decide whether to advance to systems proof or revise MVP.

## Definition Of Ready

A work item is READY FOR CODEX when:

- PO DECISION: Priority and scope are explicit.
- DESIGN — ChatGPT: Player-facing behavior and acceptance criteria are documented.
- DEVELOPMENT — Codex: Technical dependencies and test expectations are understood.
- BLOCKED: No unresolved contradiction exists with this North Star.

## Definition Of Done

A work item is done when:

- DEVELOPMENT — Codex: Implementation or documentation matches the approved scope.
- DEVELOPMENT — Codex: Relevant tests, checks, or review steps are complete.
- DESIGN — ChatGPT: Player-facing work receives design QA where applicable.
- PO DECISION: Any scope changes are logged in the decision log.
- READY FOR CODEX: The next dependent item has clear handoff notes.

## Risk Register Summary

- BLOCKED: The core physical construction loop may be too broad without a strict MVP.
- BLOCKED: Systemic interactions may create technical complexity faster than design clarity.
- BLOCKED: Visual readability may suffer if every module changes the ship without a strong art grammar.
- BLOCKED: Damage and loss may feel punitive unless the player understands cause and consequence.
- READY FOR CODEX: Risk details live in [RISK_REGISTER.md](RISK_REGISTER.md).

## Critical MVP Statement

The critical MVP is: complete encounter → receive module → attach module physically → ship visibly and mechanically changes → placement creates an interaction → module may be damaged or lost in the next encounter.

If this loop is not fun, readable, and technically stable, broader content work remains BLOCKED.

## Version History

| Version | Date | Owner | Change |
| --- | --- | --- | --- |
| 0.1 | 2026-07-19 | DEVELOPMENT — Codex | Initial governance foundation created from project assumptions. |
