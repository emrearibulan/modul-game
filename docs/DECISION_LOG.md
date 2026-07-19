# Decision Log

Use this log for durable product, design, and development decisions. New entries should include the status marker, date, owner, decision, rationale, and follow-up.

## Decisions

| ID | Date | Marker | Owner | Decision | Rationale | Follow-Up |
| --- | --- | --- | --- | --- | --- | --- |
| D-001 | 2026-07-19 | PO DECISION | Product Owner | Modul uses Godot 4. | Godot 4 supports fast iteration, 2D/3D flexibility, and accessible Windows PC builds. | DEVELOPMENT — Codex to define project scaffold criteria. |
| D-002 | 2026-07-19 | PO DECISION | Product Owner | Initial platform is Windows PC. | Focuses build, input, QA, and performance targets. | DEVELOPMENT — Codex to prepare Windows build pipeline later. |
| D-003 | 2026-07-19 | PO DECISION | Product Owner | Repository is private. | Supports early product exploration before GTM readiness. | Keep public-facing material BLOCKED until GTM gate. |
| D-004 | 2026-07-19 | PO DECISION | Product Owner | Launch scope is single-player. | Keeps the MVP centered on construction, encounters, and damage. | Multiplayer remains out of scope. |
| D-005 | 2026-07-19 | DESIGN — ChatGPT | ChatGPT | ChatGPT owns product design, design specifications, and design QA. | Design coherence requires a single accountable design owner. | Use design issue template for design-ready work. |
| D-006 | 2026-07-19 | DEVELOPMENT — Codex | Codex | Codex owns implementation, technical architecture, testing, and builds. | Technical accountability needs a single implementation owner. | Use development specifications before coding. |
| D-007 | 2026-07-19 | DESIGN — ChatGPT | ChatGPT | Pathogenic is a reference for visible physical progression and spatial component synergies. | Modul needs readable construction consequences. | Capture details in reference docs and design bible. |
| D-008 | 2026-07-19 | DESIGN — ChatGPT | ChatGPT | Noita is a reference for systemic interaction and experimentation, not full pixel simulation. | Modul should learn from emergent combinations without inheriting uncontrolled scope. | BLOCKED until specific interaction rules are approved. |
| D-009 | 2026-07-19 | DESIGN — ChatGPT | ChatGPT | Pinmoney is the graphical polish reference, not a gameplay reference. | Visual quality can guide presentation without confusing gameplay direction. | Apply during art direction and UI polish phases. |
| D-010 | 2026-07-19 | READY FOR CODEX | Codex | Documentation and governance foundation may be created before gameplay. | The project needs alignment before implementation. | This foundation PR establishes the initial document set. |

## Open Decision Queue

- BLOCKED: Exact MVP encounter type.
- BLOCKED: Initial module families and count.
- BLOCKED: Ship perspective, scale, and construction grid rules.
- BLOCKED: Whether power routing is required in MVP or deferred to systems proof.
- BLOCKED: Damage model severity and recovery economy.
