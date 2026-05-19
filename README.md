# creative-ideation

Creative Generation Engine — transforms research hypotheses into diverse solution spaces via 10 parallel creativity campaigns spanning structural, analogical, destructive, and combinatorial methods.

## Architecture

```
ENTRY.md
  └── Campaign (10) — self-contained creative activity domain
        └── Strategy (5 per campaign) — iterative framework with budget + state ledger
              └── Tactic (2-3 per campaign) — SOP combination principle
                    └── SOP — single operation (subagent or import)
```

## Campaigns

| # | Campaign | Method Family |
|---|----------|--------------|
| 1 | structural-deconstruction | SCAMPER, TRIZ, SIT |
| 2 | cross-domain-discovery | Bisociation, analogical transfer |
| 3 | assumption-destruction | Axiom negation, reverse brainstorming |
| 4 | biomimicry | Design Spiral, BioTRIZ |
| 5 | synectics | Gordon's 4 analogy types |
| 6 | morphological-exploration | Zwicky box, CCA, GMA |
| 7 | lateral-thinking | de Bono PO/movement |
| 8 | combinatorial-creativity | Fauconnier-Turner blending |
| 9 | perspective-forcing | Six Hats, role-based |
| 10 | systematic-enumeration | Coverage analysis, failure taxonomy |

## Dependencies

- `web-browsing` — web-search + web-research SOPs
- `literature-engine` — paper-overview + paper-search + paper-research SOPs
- `subagent-spawning` — subagent dispatch conventions
- `context-management` — checkpoint protocol

## Usage

This repo is consumed by the CC (Claude Conductor) orchestration layer. CC reads ENTRY.md, routes to the appropriate campaign(s), and executes strategies with budget tracking.

## Scope

This engine STOPS at idea generation. It does NOT converge, validate, or implement.
