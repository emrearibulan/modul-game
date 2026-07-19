# Product Charter

## Purpose

Modul exists to prove a clear design promise: a player can build a spacecraft as a physical object, survive with it, change it through earned modules, and watch that object become more powerful, stranger, and more vulnerable because of their own construction choices.

## Product Assumptions

- PO DECISION: Engine is Godot 4.
- PO DECISION: Initial platform is Windows PC.
- PO DECISION: Repository is private.
- PO DECISION: Launch scope is single-player.
- PO DECISION: Gameplay implementation is not part of the foundation milestone.

## Audience

- DESIGN — ChatGPT: Players who enjoy construction, experimentation, systemic interactions, and meaningful loss.
- DESIGN — ChatGPT: Players who want their build decisions to be visible in the play space rather than hidden in menus.

## Differentiator

Modul's differentiator is player-authored physical spacecraft construction. Every major module must visibly alter the ship, and module placement should eventually matter through orientation, power routing, exposure, adjacency, and damage.

## MVP Promise

READY FOR CODEX once specified: complete encounter → receive module → attach module physically → ship visibly and mechanically changes → placement creates an interaction → module may be damaged or lost in the next encounter.

## Ownership

- DESIGN — ChatGPT: Product design, design specifications, design QA, and reference-game interpretation.
- DEVELOPMENT — Codex: Implementation, technical architecture, testing, build process, and technical QA.
- PO DECISION: Scope approval, priority, release gates, and business-facing decisions.

## Success Measures

- DESIGN — ChatGPT: Players can describe how their ship changed after attaching a module.
- DESIGN — ChatGPT: Players understand why placement affected an outcome.
- DESIGN — ChatGPT: Players feel module damage or loss was consequential, readable, and recoverable.
- DEVELOPMENT — Codex: The MVP loop runs end to end in Godot 4 with repeatable tests and Windows PC builds.

## Non-Goals

- BLOCKED: Full Noita-style pixel/material simulation.
- BLOCKED: Multiplayer launch scope.
- BLOCKED: Content expansion before MVP validation.
- BLOCKED: Gameplay implementation before design-ready MVP specifications.
