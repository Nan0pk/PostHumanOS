# PostHumanOS

**PostHumanOS** is a speculative but disciplined systems research program for an AI-mediated, physics-aware, intent-driven operating architecture.

It asks whether future operating environments can move beyond file/process/driver-centric metaphors toward a control loop based on formal intent, hardware capability contracts, physical telemetry, deterministic admission gates, semantic state graphs, and auditable provenance.

## One-Sentence Summary

PostHumanOS studies how to convert high-level intent into safe, measurable, resource-aware machine-state transitions without granting unchecked autonomy to AI-generated actions.

## What This Repository Is

This repository is a research and architecture workspace. It contains:

- a fully cited academic paper draft;
- a foundation dossier with claim decomposition and research programs;
- prior-art, novelty, citation, and bibliography artifacts;
- an engineering roadmap for 12–24 months of R&D;
- initial documentation for contributors, research programs, prototype wedges, and AI agents.

## What This Repository Is Not

PostHumanOS is **not yet**:

- a bootable operating system;
- a replacement kernel;
- an unrestricted autonomous AI agent;
- a claim that files, drivers, source code, or privilege boundaries can simply be deleted;
- a product roadmap promising near-term full implementation.

The project’s current purpose is to turn a radical architecture into decomposable, falsifiable, citation-aware research and engineering work.

## Core Architectural Invariants

1. **No autonomy without admissibility.**  
   Any AI-generated or adaptive action that changes machine state must pass deterministic verification, sandboxing, policy checks, or proof-carrying admission.

2. **No abstraction collapse without governance replacement.**  
   If files, drivers, source code, or privilege boundaries are reduced, their hidden functions — provenance, audit, recovery, compatibility, debugging, and accountability — must be replaced.

3. **No fluidity without transition economics.**  
   Dynamic topologies, migrations, caches, execution morphologies, and accelerator remappings must account for formation, synchronization, verification, rollback, and teardown costs.

4. **No physicalism without instrumentation.**  
   Energy and thermodynamic claims must map to measurable counters and actuators such as RAPL, DVFS, thermal sensors, memory bandwidth, accelerator occupancy, network quality, and latency.

## Canonical Control Loop

```text
Formal Intent
    ↓
Capability Contracts / Telemetry
    ↓
Multi-Currency Planning
    ↓
Deterministic Admission
    ↓
Bounded Execution
    ↓
Semantic State + Provenance
    ↓
Audit / Rollback / Adaptation
```

AI models may assist with interpretation, planning, code generation, or explanation, but they do not directly earn authority to mutate machine state. Authority comes from admission evidence.

## Repository Map

| Path | Purpose |
|---|---|
| [`research/`](research/) | Academic papers, foundation dossier, citation backbone, bibliography, prior-art and novelty matrices. |
| [`docs/`](docs/) | Human-readable overview, core concepts, glossary, FAQ, and architectural guidance. |
| [`programs/`](programs/) | Modular work packages for Programs A–J. |
| [`prototypes/`](prototypes/) | Initial engineering wedges intended for bounded implementation. |
| [`diagrams/`](diagrams/) | Mermaid diagrams for the architecture and roadmap. |
| [`adr/`](adr/) | Architecture Decision Records preserving core methodological decisions. |
| [`AGENTS.md`](AGENTS.md) | Canonical instructions for AI agents working in this repository. |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Contribution rules and research discipline. |
| [`ROADMAP.md`](ROADMAP.md) | Short actionable roadmap derived from the full engineering roadmap. |

## Recommended Reading Paths

### For New Readers

1. [`docs/00_overview.md`](docs/00_overview.md)
2. [`docs/05_glossary.md`](docs/05_glossary.md)
3. [`research/posthumanos_executive_prospectus.md`](research/posthumanos_executive_prospectus.md)
4. [`ROADMAP.md`](ROADMAP.md)

### For Researchers

1. [`research/posthumanos_fully_cited_paper.md`](research/posthumanos_fully_cited_paper.md)
2. [`research/posthumanos_paper_foundation.md`](research/posthumanos_paper_foundation.md)
3. [`research/posthumanos_annotated_bibliography.md`](research/posthumanos_annotated_bibliography.md)
4. [`research/posthumanos_prior_art_matrix.md`](research/posthumanos_prior_art_matrix.md)
5. [`research/posthumanos_novelty_overlap_map.md`](research/posthumanos_novelty_overlap_map.md)

### For Engineers

1. [`research/posthumanos_engineering_roadmap.md`](research/posthumanos_engineering_roadmap.md)
2. [`programs/README.md`](programs/README.md)
3. [`prototypes/README.md`](prototypes/README.md)
4. [`docs/04_near_term_prototypes.md`](docs/04_near_term_prototypes.md)

### For AI Agents

Read [`AGENTS.md`](AGENTS.md) before making changes. The master instruction is: preserve ambition, but decompose every claim into mechanisms, constraints, evidence, and testable steps.

## Research Programs

PostHumanOS is decomposed into ten programs:

| Program | Topic |
|---|---|
| A | Formal Intent Representation and Fulfillment Semantics |
| B | Capability Ontology, Telemetry Normalization, and Universal Capability Contracts |
| C | Safe Discovery of Unknown Hardware and Bounded Probe Architectures |
| D | Intent-Based Orchestration and Multi-Currency Runtime Control |
| E | Dynamic Machine Morphology and Transition Economics |
| F | Semantic-State Persistence and Filesystem Replacement Analysis |
| G | Structural Compilation, Post-Syntactic Execution, and Certifiable Generation |
| H | Trust Architecture, Deterministic Admission, and Proof-Bounded Execution |
| I | Environmental Embodiment and Policy-Aware Adaptive Networking |
| J | Governance, Explainability, Provenance, and Compatibility Projection |

See [`programs/README.md`](programs/README.md) for the modular program index.

## Near-Term Prototype Wedges

The first engineering work should be bounded prototypes, not a full OS rewrite:

1. telemetry-aware scheduler;
2. UCC parser and capability registry;
3. semantic storage overlay;
4. sandboxed probing emulator;
5. restricted verified code DSL.

See [`prototypes/README.md`](prototypes/README.md).

## Current Status

The repository currently contains the research foundation and initial navigation structure. The next work should formalize schemas, benchmarks, and prototype READMEs into runnable experimental artifacts.

## Contributing

Read [`CONTRIBUTING.md`](CONTRIBUTING.md). Contributions should preserve the no-dismissal methodology: do not remove ambitious ideas because they appear difficult; decompose them into claims, mechanisms, assumptions, dependencies, risks, and validation paths.
