# Master Backlog

This backlog tracks product, design, and development work across the project. Every item should carry one of the required markers.

## Foundation

| ID | Marker | Owner | Item | Acceptance |
| --- | --- | --- | --- | --- |
| FND-001 | READY FOR CODEX | Codex | Create documentation and governance foundation. | Core docs, specification folders, references, game placeholder, issue templates, and PR template exist. |
| FND-002 | DEVELOPMENT — Codex | Codex | Create Godot 4 project scaffold. | `game/` contains a valid Godot 4 project with no gameplay beyond scaffold requirements. |
| FND-003 | DESIGN — ChatGPT | ChatGPT | Draft MVP design specification. | MVP loop behavior, module rules, and acceptance criteria are documented. |
| FND-004 | PO DECISION | Product Owner | Approve MVP scope. | Scope is approved or revised in the decision log. |

## Critical MVP

| ID | Marker | Owner | Item | Acceptance |
| --- | --- | --- | --- | --- |
| MVP-001 | DESIGN — ChatGPT | ChatGPT | Define first complete encounter. | Encounter start, win condition, failure state, reward trigger, and readability goals are specified. |
| MVP-002 | DESIGN — ChatGPT | ChatGPT | Define reward module flow. | Player receives a module after a completed encounter and understands its purpose. |
| MVP-003 | DESIGN — ChatGPT | ChatGPT | Define physical attachment rules. | Attachment points, orientation, invalid placement, and feedback are specified. |
| MVP-004 | DEVELOPMENT — Codex | Codex | Implement module attachment prototype. | A module attaches physically and changes ship visuals and mechanics. |
| MVP-005 | DEVELOPMENT — Codex | Codex | Implement placement interaction prototype. | Placement creates at least one mechanical interaction in the next encounter. |
| MVP-006 | DEVELOPMENT — Codex | Codex | Implement damage or loss prototype. | A module can be damaged, disabled, severed, or lost with readable feedback. |
| MVP-007 | DEVELOPMENT — Codex | Codex | Implement end-to-end MVP loop. | Encounter, reward, attachment, changed ship behavior, placement interaction, and subsequent risk are playable. |

## Systems

| ID | Marker | Owner | Item | Acceptance |
| --- | --- | --- | --- | --- |
| SYS-001 | BLOCKED | ChatGPT | Define power routing rules. | Routing rules are clear enough for UI, data, failure cases, and tests. |
| SYS-002 | BLOCKED | ChatGPT | Define orientation effects. | Module rotation has intentional consequences and clear player feedback. |
| SYS-003 | BLOCKED | ChatGPT | Define exposure and shielding rules. | Exposed modules have readable risk and mitigation rules. |
| SYS-004 | DEVELOPMENT — Codex | Codex | Data-driven module definitions. | Modules can be authored through data resources rather than hardcoded scene logic. |
| SYS-005 | DEVELOPMENT — Codex | Codex | Deterministic simulation tests. | Core module interactions can be tested without manual play. |

## Presentation

| ID | Marker | Owner | Item | Acceptance |
| --- | --- | --- | --- | --- |
| ART-001 | DESIGN — ChatGPT | ChatGPT | Define ship visual grammar. | Players can read hull, module role, damage, attachment, and exposure at a glance. |
| ART-002 | DESIGN — ChatGPT | ChatGPT | Translate Pinmoney polish into Modul rules. | Polish guidance is concrete and does not imply gameplay copying. |
| ART-003 | DEVELOPMENT — Codex | Codex | Implement visual feedback hooks. | Attachment, damage, loss, and module state changes expose signals for effects and UI. |

## Build And QA

| ID | Marker | Owner | Item | Acceptance |
| --- | --- | --- | --- | --- |
| QA-001 | DEVELOPMENT — Codex | Codex | Define automated test tiers. | Unit, integration, scene, and smoke test expectations are documented. |
| QA-002 | DEVELOPMENT — Codex | Codex | Create Windows PC build workflow. | A repeatable local or CI build produces a Windows artifact. |
| QA-003 | DESIGN — ChatGPT | ChatGPT | Create design QA checklist. | Playtest questions and comprehension checks align to the MVP loop. |

## GTM

| ID | Marker | Owner | Item | Acceptance |
| --- | --- | --- | --- | --- |
| GTM-001 | BLOCKED | Product Owner | Decide public product positioning. | Store pitch, naming, pricing, and launch channel are approved. |
| GTM-002 | BLOCKED | ChatGPT | Draft store page claim set. | Claims are backed by implemented, tested features. |
| GTM-003 | BLOCKED | Codex | Produce release candidate build. | Build passes technical QA and stage-gate criteria. |
