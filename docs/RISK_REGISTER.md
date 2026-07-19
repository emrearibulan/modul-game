# Risk Register

Use this register to track product, design, technical, and production risks. Status markers should be updated as risks are clarified, accepted, mitigated, or closed.

| ID | Marker | Risk | Impact | Mitigation | Owner |
| --- | --- | --- | --- | --- | --- |
| R-001 | BLOCKED | Physical construction scope becomes too large before the MVP loop is proven. | High | Build only the critical MVP loop first. | PO DECISION |
| R-002 | BLOCKED | Module placement rules are hard to understand. | High | Require design QA for placement readability. | DESIGN — ChatGPT |
| R-003 | BLOCKED | Noita-inspired systemic interactions expand into full simulation scope. | High | Explicitly exclude full pixel simulation and approve each systemic layer. | DESIGN — ChatGPT |
| R-004 | BLOCKED | Every major module visibly altering the ship increases asset and layout complexity. | Medium | Define a compact visual grammar before content expansion. | DESIGN — ChatGPT |
| R-005 | BLOCKED | Damage and loss feel unfair or punitive. | High | Make exposure, cause, and consequence visible. | DESIGN — ChatGPT |
| R-006 | BLOCKED | Power routing becomes a hidden spreadsheet system. | Medium | Keep routing spatial, inspectable, and deferred until MVP clarity exists. | DESIGN — ChatGPT |
| R-007 | DEVELOPMENT — Codex | Godot architecture becomes scene-script-heavy and hard to test. | High | Keep core rules in testable state/services with scene adapters. | Codex |
| R-008 | DEVELOPMENT — Codex | Windows build workflow is delayed until late production. | Medium | Add build pipeline early after scaffold approval. | Codex |
| R-009 | PO DECISION | Private repository delays external feedback. | Medium | Use a private playtest gate before GTM decisions. | Product Owner |
| R-010 | READY FOR CODEX | Governance exists before gameplay work begins. | Low | Keep documentation current through PR and issue templates. | Codex |

## Risk Review Cadence

- PO DECISION: Review high-impact risks at each stage gate.
- DESIGN — ChatGPT: Review design risks during design QA and playtest synthesis.
- DEVELOPMENT — Codex: Review technical risks before implementation milestones and build gates.
