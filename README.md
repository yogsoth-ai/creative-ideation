<!-- markdownlint-disable -->
<div align="center">

> *The greatest breakthroughs don't come from thinking harder within existing frames — they come from shattering the frame entirely and discovering what lies beyond.*

</div>

# 💡 Creative Ideation

*Divergent idea generation engine for autonomous research pipelines.*

**Creative Ideation is not a brainstorming helper.** It is a systematic creativity machine that transforms research hypotheses into diverse solution spaces via 10 parallel campaigns spanning structural, analogical, destructive, and combinatorial methods. It generates — it does not converge, validate, or implement.

---

## ⚡ What It Does

- 🏗️ **Structural deconstruction** — SCAMPER, TRIZ contradiction resolution, component surgery, and trimming to reshape existing solutions
- 🌉 **Cross-domain discovery** — bisociation networks, analogical transfer, and design-by-analogy to import solutions from unrelated fields
- 💥 **Assumption destruction** — axiom negation, reverse brainstorming, sacred cow hunting, and anti-benchmarking to break paradigmatic constraints
- 🦎 **Biomimicry** — Design Spiral, BioTRIZ, organism discovery, and biological strategy extraction for nature-inspired solutions
- 🔮 **Synectics** — Gordon's four analogy types (direct, personal, symbolic, fantasy) with excursion methods
- 📐 **Morphological exploration** — Zwicky box, cross-consistency analysis, and general morphological analysis for systematic combination enumeration
- 🎲 **Lateral thinking** — de Bono PO provocations, random entry, concept fan, and movement extraction
- 🧬 **Combinatorial creativity** — Fauconnier-Turner conceptual blending, recombination architecture, and forced connections
- 🎭 **Perspective forcing** — Six Hats rotation, role-based ideation, temporal projection, and stakeholder simulation
- 📊 **Systematic enumeration** — benchmark sweep, method-problem matrix, failure taxonomy, and factorial ideation

---

## 🎯 Design Philosophy

Each campaign is a self-contained creative domain with its own strategies, tactics, and subagent SOPs. The engine enforces quantitative budget floors via State Ledgers and HARD-GATEs — creativity is systematic, not random. Saturation detection prevents infinite loops while ensuring sufficient exploration depth.

The engine STOPS at idea generation. Convergence, validation, and implementation belong to downstream repos.

---

## 🏗️ Architecture

```bash
┌─────────────────────────────────────────────────────┐
│                     ENTRY.md                         │
│         (routing table + orchestration)              │
├─────────────────────────────────────────────────────┤
│                                                     │
│  Campaign (10)  — self-contained creative domain    │
│    └── Strategy (5 per campaign)                    │
│          └── Tactic (2-3 per campaign)              │
│                └── SOP (subagent or import)          │
│                                                     │
├─────────────────────────────────────────────────────┤
│  Shared Components                                  │
│  ├── 5 import SOPs (web-search, paper-overview...)  │
│  ├── 9 shared subagent SOPs (saturation, novelty..) │
│  └── 4 shared tactics (evaluation, provocation...)  │
└─────────────────────────────────────────────────────┘
```

## 📋 Campaign Inventory

| # | Campaign | Method Family | Strategies |
|---|----------|--------------|------------|
| 1 | structural-deconstruction | SCAMPER, TRIZ, SIT | 5 |
| 2 | cross-domain-discovery | Bisociation, analogical transfer | 5 |
| 3 | assumption-destruction | Axiom negation, reverse brainstorming | 5 |
| 4 | biomimicry | Design Spiral, BioTRIZ | 5 |
| 5 | synectics | Gordon's 4 analogy types | 5 |
| 6 | morphological-exploration | Zwicky box, CCA, GMA | 5 |
| 7 | lateral-thinking | de Bono PO/movement | 5 |
| 8 | combinatorial-creativity | Fauconnier-Turner blending | 5 |
| 9 | perspective-forcing | Six Hats, role-based | 5 |
| 10 | systematic-enumeration | Coverage analysis, failure taxonomy | 5 |

## 🔗 Dependencies

| Dependency | Provides |
|------------|----------|
| `web-browsing` | web-search + web-research SOPs |
| `literature-engine` | paper-overview + paper-search + paper-research SOPs |
| `subagent-spawning` | Subagent dispatch conventions |
| `context-management` | Checkpoint protocol |

## 🛠️ MCP Tools

| Tool | Server | Purpose |
|------|--------|---------|
| brave_web_search | brave-search | General web search |
| brave_llm_context | brave-search | Deep content extraction |
| apify/rag-web-browser | apify | Full page scraping |
| get_paper_content | alphaxiv | Academic paper content |
| discover_papers | alphaxiv | Paper discovery |
| relevanceSearch | semantic-scholar | Literature search |
| paper | semantic-scholar | Paper details |
| citations | semantic-scholar | Citation networks |

## 📊 Stats

- **188** skill directories
- **287** total files
- **10** campaigns × **5** strategies each = **50** strategies
- **99** subagent SOPs with prompt templates
- **4** shared tactics + campaign-specific tactics

## 📄 License

[Apache-2.0](LICENSE)

---

*Part of the [Yogsoth AI](https://github.com/yogsoth-ai) ecosystem. Built by [Pthahnix](https://github.com/Pthahnix).*
