# PostHumanOS Citation Backbone

## Purpose of This File
This document maps the manuscript sections in `posthumanos_full_paper_draft.md` to:
- the major claims they make,
- the companion analytical basis in `posthumanos_paper_foundation.md`,
- the currently available seed sources in `posthumanos_seed_bibliography.md`,
- and the citation gaps that still need to be filled.

The goal is not only to insert citations, but to ensure that every major claim in the paper is supported at the correct level:
- foundational theory,
- current systems precedent,
- cautionary limitation,
- or open-gap statement.

This file is designed to guide the next drafting phase, where the manuscript is turned into a more formally sourced paper.

---

## 1. Citation Types Used in This Backbone

### T1 — Foundational Theory Citation
Used when the paper makes a claim about rigorous theoretical grounding.
Examples:
- physical embodiment of computation,
- formal goals and operationalization,
- proof-carrying or formally verified systems.

### T2 — Adjacent Systems Precedent Citation
Used when the paper claims that something already exists in partial form.
Examples:
- cross-layer optimization,
- hardware description frameworks,
- heterogeneous scheduling,
- semantic persistence,
- multipath networking.

### T3 — Cautionary / Constraint Citation
Used where the paper emphasizes that precedent is narrow, partial, or historically constrained.
Examples:
- verified kernels are rare and expensive,
- intent-driven systems are domain-limited,
- provenance is not yet governance replacement.

### T4 — Open Gap / Frontier Citation
Used where the paper explicitly says a problem remains unsolved.
Examples:
- AI-generated proof-carrying execution,
- safe autonomous hardware probing,
- trust substitution at architectural scale.

---

## 2. Section-by-Section Citation Backbone

## 2.1 Abstract

### Major Claims
- PostHumanOS is a decomposable systems research program rather than a directly buildable near-term OS.
- The architecture combines physicalist computation framing, abstraction critique, intent-driven orchestration, machine legibility, and formal governance.
- The value lies in identifying recurring bridge problems.

### Current Source Status
- Mostly synthesized from the foundation dossier and prior-art matrix.
- Does not require dense direct citation, but should be consistent with the paper’s later citations.

### Citation Need
- Light citation only if journal style prefers abstract references omitted.

### Gap Status
- None urgent.

---

## 2.2 Section 1 — Introduction

### Major Claims
- PostHumanOS is a systems thesis rather than a software implementation.
- Contemporary OS architecture still reflects older assumptions around opacity, manual programming, rigid privilege separation, and file-centric persistence.
- The paper’s method is decomposition rather than dismissal.

### Foundation Support
- Sections 5–16 of the foundation dossier.

### Current Candidate Sources
- Goal-oriented/intent operationalization sources [A1, A2]
- Hardware-description and verification sources [B1, H1, H2]

### Citation Type Needed
- T2 for “adjacent precedent exists in multiple areas”
- T3 for “current systems remain fragmented and domain-bound”

### Citation Gaps
- Historical OS abstraction critiques and architectural alternatives need explicit canonical citations.
- Exokernel/library OS/microkernel sources still need to be added to the bibliography.

---

## 2.3 Section 2 — Methodological Stance and Analytical Framework

### Major Claims
- Maximum-charity technical reading.
- No-dismissal principle.
- Decomposition-before-judgment.
- Replacement claims must replace functions, not just names.

### Foundation Support
- Method section in the paper foundation.

### Current Candidate Sources
- Mostly internal methodological framing.

### Citation Type Needed
- Generally none required, unless the paper wants to cite speculative design or systems-methodology traditions.

### Citation Gaps
- Optional: methodological literature on socio-technical systems analysis or design research.

---

## 2.4 Section 3 — Thesis Restatement in Neutral Research Language

### Major Claims
- Computation is physically embodied.
- Many dominant abstractions are historically contingent.
- Hardware, intent, and proof-bearing control may support different architectures.

### Current Candidate Sources
- Goal operationalization and intent sources [A1, A2]
- Hardware description sources [B1]
- Verification and kernel assurance sources [H1, H2]

### Citation Type Needed
- T1 for physical and formal claims
- T2 for capability and verification precedent

### Citation Gaps
- Need direct physical-computation sources beyond systems-adjacent energy work.
- Need explicit sources on thermodynamics/information theory and cost of data movement.

---

## 2.5 Section 5 — Foundational Ontology of Computation

### Major Claims
- Physical cost is central to computation.
- Intent-like and declarative control already exist in narrower forms.
- Legacy abstractions are contingent, but not trivially disposable.

### Current Candidate Sources
- KAOS / goal-oriented RE [A1]
- Intent-driven service management [A2]

### Citation Type Needed
- T1 for formal goals and operationalization [A1]
- T2 for intent-like operational systems [A2]
- T3 for the limits of current intent systems [A2]

### Citation Gaps
- Strong need for foundational thermodynamics-of-computation and data-movement literature.
- Need sources on abstraction cost and OS design history.

---

## 2.6 Section 6 — Post-Stack Architecture and Hardware Legibility

### Major Claims
- Hardware description and cross-layer responsibility redistribution already have precedent.
- ACPI/device descriptions show structured hardware legibility exists in partial form.
- A richer capability contract remains missing.

### Current Candidate Sources
- ACPI namespace and enumeration documentation [B1]
- Hardware discovery/context explanation sources [B2]

### Citation Type Needed
- T2 for current structured hardware description [B1]
- T3 for the limitations of current enumeration/description models [B1, B2]

### Citation Gaps
- Need exokernel, library OS, and cross-layer optimization research citations.
- Need sources on userspace drivers or accelerator runtime boundary collapse.

---

## 2.7 Section 7 — Hardware Discovery, Adaptation, and Safe Probing

### Major Claims
- Hardware discovery can be decomposed into system identification, inference, quarantine, and constrained synthesis.
- Existing techniques suggest fragments of this, but not a safe autonomous OS service.

### Current Candidate Sources
- No strong dedicated seed sources yet beyond general hardware discovery context [B2]
- Trust and verification sources [H1, H2, H3] are indirectly relevant

### Citation Type Needed
- T2 for hardware probing and discovery context [B2]
- T4 for “safe autonomous hardware discovery remains unsolved”

### Citation Gaps
- Major gap area.
- Need dedicated sources on:
  - hardware/firmware fuzzing,
  - protocol inference,
  - safe exploration,
  - IOMMU/DMA containment,
  - system identification.

---

## 2.8 Section 8 — Intent-Based Orchestration and Multi-Currency Control

### Major Claims
- Multi-objective and energy-aware scheduling already exist.
- Richer orchestration is plausible but still lacks formal intent semantics.
- Learned control is possible in bounded domains but risky if unconstrained.

### Current Candidate Sources
- Data center RL and energy optimization survey [D1]
- GPU scheduling survey [D2]
- Heterogeneous dynamic partitioning source [D3]
- Intent sources [A1, A2]

### Citation Type Needed
- T2 for heterogeneous, energy-aware, multi-objective scheduling [D1, D2, D3]
- T3 for domain-boundedness and control limitations [D1, D2]
- T1/T2 for intent semantics from goal-oriented sources [A1, A2]

### Citation Gaps
- Need more canonical scheduler and control-theory sources.
- Need sources on constrained/safe RL and hierarchical systems control.

---

## 2.9 Section 9 — Dynamic Machine Morphology

### Major Claims
- Reconfiguration, transient structures, and dynamic placement already exist in multiple domains.
- The thesis becomes distinctive when these are unified into a machine-level architectural principle.
- Transition economics is the real deciding factor.

### Current Candidate Sources
- Dynamic partitioning / runtime variant selection [D3]
- Indirect support from scheduling surveys [D2]

### Citation Type Needed
- T2 for existing runtime adaptation and heterogeneous remapping [D3]
- T3 for why transition economics remains underdeveloped

### Citation Gaps
- Need explicit burst buffer, autoscaling, runtime graph optimization, and migration-cost literature.
- Need sources on phase-aware optimization and anti-thrashing control.

---

## 2.10 Section 10 — Storage, State, and Persistence

### Major Claims
- Semantic and graph-like persistence models exist.
- Filesystems carry many hidden governance and interoperability roles.
- Hybrid semantic overlays are a more credible bridge than abrupt replacement.

### Current Candidate Sources
- None yet in the seed bibliography dedicated to storage.

### Citation Type Needed
- T2 for graph/object/state persistence precedent
- T3 for filesystem hidden-function burden and ecosystem lock-in

### Citation Gaps
- Major gap area.
- Need sources on:
  - filesystem architecture,
  - object stores,
  - graph databases,
  - content-addressed systems,
  - autosave/live-state tools,
  - provenance/versioning/archival semantics.

---

## 2.11 Section 11 — Programming, Compilation, and Post-Syntactic Execution

### Major Claims
- Structural IRs and synthesis are real.
- Post-source development is plausible only in narrow, certifiable pipelines.
- Source-code governance must be replaced explicitly if source centrality is reduced.

### Current Candidate Sources
- Automatic kernel code synthesis and verification [H3]
- Verified systems lessons [H1]
- Goal operationalization sources [A1] as upstream semantic precursors

### Citation Type Needed
- T2 for narrow certifiable generation precedent [H3]
- T3 for the difficulty of scaling such methods [H3, H1]
- T1 for operationalization/refinement precursors [A1]

### Citation Gaps
- Need verified compilation, translation validation, IR/DSL, synthesis, and automatic programming history sources.
- Need sources on provenance beyond source code.

---

## 2.12 Section 12 — Security, Trust, and Formal Assurance

### Major Claims
- Proof can replace some defensive roles in narrow domains.
- Verified kernels and proof-bearing execution are real but highly constrained.
- Trust substitution at scale remains unresolved.

### Current Candidate Sources
- seL4 verification paper [H1]
- Lessons from formally verified deployed systems [H1]
- Practical formal methods survey [H1]
- Certified kernels / proof-carrying direction source [H2]
- Automatic kernel code synthesis and verification [H3]

### Citation Type Needed
- T1 for formal assurance precedent [H1, H2]
- T2 for deployed verified-system evidence [H1]
- T3 for the narrowness and cost of such approaches [H1, H3]
- T4 for unresolved AI-generated certifiable execution [H3 plus open-gap framing]

### Citation Gaps
- Need explicit proof-carrying code canonical citations.
- Need capability system and software fault isolation sources.
- Need deterministic verifier/admission-control sources beyond current seed set.

---

## 2.13 Section 13 — Environmental Embodiment and Adaptive Networking

### Major Claims
- Context-aware adaptation already exists in bounded forms.
- Multipath and adaptive transport already exist in bounded forms.
- Biometrics and broad embodied optimization require much stronger policy constraints.

### Current Candidate Sources
- None yet in the current seed bibliography dedicated specifically to embodiment/networking.

### Citation Type Needed
- T2 for context-aware computing and multipath networking precedent
- T3 for privacy and policy limitations

### Citation Gaps
- Major gap area.
- Need sources on:
  - context-aware computing,
  - adaptive mobile sensing,
  - multipath transport,
  - SD-WAN/link bonding,
  - cognitive radio,
  - privacy/biometric governance.

---

## 2.14 Section 14 — Cross-Section Grounding Synthesis

### Major Claims
- Many ingredients are real in isolation.
- The main novelty lies in synthesis and convergence around shared bottlenecks.

### Current Candidate Sources
- Draws on all previous section sources
- Prior-art matrix and novelty map summarize the logic

### Citation Type Needed
- T2/T3 combination, distributed across sections rather than concentrated here

### Citation Gaps
- None unique, but this section depends on all earlier sections being well sourced.

---

## 2.15 Section 15 — Hardest Convergence Bottlenecks

### Major Claims
- Formal intent, machine legibility, admissibility/verification, governance replacement, and transition economics are the key bottlenecks.

### Current Candidate Sources
- Formal intent: [A1, A2]
- Legibility: [B1, B2]
- Verification/trust: [H1, H2, H3]
- Governance/provenance: [J1, J2]
- Orchestration: [D1, D2, D3]

### Citation Type Needed
- Mostly synthesized from program analysis and prior-art comparisons
- Each bottleneck should cite representative supporting sections/sources rather than stand alone unsourced

### Citation Gaps
- Transition economics remains thinly sourced.
- Governance replacement beyond software provenance needs more sources.

---

## 2.16 Section 16 — Global Dependency Graph

### Major Claims
- The architecture has ordered dependency layers.
- Some programs are foundational and others are downstream multipliers.

### Current Candidate Sources
- Mostly internal synthesis from the foundation dossier

### Citation Type Needed
- Usually none directly, unless citing systems dependency-analysis methods.

### Citation Gaps
- Not urgent.

---

## 2.17 Section 17 — Bridge-Architecture Ladders

### Major Claims
- Ambitious concepts can be decomposed into staged bridge sequences.
- Hybrid, template-driven, constrained forms are the correct near bridges.

### Current Candidate Sources
- Intent formalization: [A1, A2]
- UCC/capability: [B1, B2]
- Trust/generation: [H1, H2, H3]
- Orchestration: [D1, D2, D3]
- Governance/provenance: [J1, J2]

### Citation Type Needed
- T2 for each bridge stage where precedent exists
- T4 where the bridge reaches beyond current precedent

### Citation Gaps
- Storage bridges, hardware-discovery bridges, and adaptive-network bridges need stronger source coverage.

---

## 2.18 Section 18 — Execution-Ready Research Programs

### Major Claims
- The thesis decomposes into ten assignable research programs.
- Programs A, B, and H are deepest core; D operationalizes; J runs in parallel.

### Current Candidate Sources
- A: [A1, A2]
- B: [B1, B2]
- D: [D1, D2, D3]
- H: [H1, H2, H3]
- J: [J1, J2]

### Citation Type Needed
- T2/T3 for programs with strong prior-art grounding
- T4 for frontier programs such as C and broad G claims

### Citation Gaps
- C, E, F, and I need more direct bibliography support.
- G needs broader synthesis and verified compilation sources.

---

## 2.19 Section 19 — Research-Execution Discipline

### Major Claims
- No autonomy without admissibility.
- No abstraction collapse without governance replacement.
- No fluidity without transition economics.

### Current Candidate Sources
- H1/H2/H3 support admissibility logic.
- J1/J2 support provenance/governance logic.
- D1/D2/D3 partially support cost-aware control logic.

### Citation Type Needed
- Mostly normative synthesis, lightly supported by representative prior-art references.

### Citation Gaps
- Transition economics still needs stronger direct support.

---

## 2.20 Section 20 — Conclusion

### Major Claims
- PostHumanOS should be treated as a structured frontier program.
- Its value lies in exposing recurring bottlenecks, not in claiming every mechanism is near-term.

### Current Candidate Sources
- Synthesized from the full paper and dossier.

### Citation Type Needed
- Usually minimal; conclusion can echo earlier support.

### Citation Gaps
- None unique.

---

## 3. Citation Gap Summary by Urgency

## 3.1 Highest-Urgency Gaps
These are the missing literature areas that most limit the paper’s current grounding.

### Gap A — Thermodynamics / Physical Cost Foundations
Needed for:
- Section 5
- physicalist framing claims

Need sources on:
- thermodynamics of computation,
- Landauer principle,
- cost of data movement,
- physical cost models in computing systems.

### Gap B — Cross-Layer / Exokernel / Architectural Alternatives
Needed for:
- Section 6
- stack critique and osmotic architecture

Need sources on:
- exokernels,
- library OS,
- microkernels,
- userspace drivers,
- cross-layer optimization.

### Gap C — Safe Hardware Discovery and Containment
Needed for:
- Section 7
- Program C

Need sources on:
- hardware fuzzing,
- protocol inference,
- safe exploration,
- IOMMU/DMA containment,
- system identification.

### Gap D — Storage and Filesystem Alternatives
Needed for:
- Section 10
- Program F

Need sources on:
- filesystems,
- graph/object stores,
- content-addressed storage,
- semantic persistence,
- live-state systems,
- archival/provenance models.

### Gap E — Verified Compilation / Synthesis / Automatic Programming History
Needed for:
- Section 11
- Program G

Need sources on:
- verified compilation,
- translation validation,
- DSL/IR-centered workflows,
- synthesis,
- automatic programming history.

### Gap F — Embodiment / Multipath / Privacy
Needed for:
- Section 13
- Program I

Need sources on:
- context-aware computing,
- multipath networking,
- adaptive transport,
- cognitive radio,
- privacy and biometric governance.

---

## 3.2 Medium-Urgency Gaps

### Gap G — Transition Economics and Reconfiguration Cost Literature
Needed for:
- Section 9
- Section 15
- Program E

### Gap H — Governance Beyond Provenance
Needed for:
- Section 10, 11, 12, 13
- Program J

Need sources on:
- migration studies,
- explainability beyond model XAI,
- socio-technical system governance,
- compatibility and transition costs.

---

## 4. Suggested Next Citation-Building Steps

### Step 1
Expand the seed bibliography with the highest-urgency gaps:
- thermodynamics / data movement,
- exokernel/cross-layer,
- safe hardware probing,
- storage alternatives,
- verified compilation,
- embodiment/networking/privacy.

### Step 2
Create a second-pass bibliography file or extend the existing one with:
- Program C,
- Program E,
- Program F,
- Program G,
- Program I.

### Step 3
After that, revise `posthumanos_full_paper_draft.md` and insert source references section by section.

---

## 5. Recommended Follow-On File

The best next derivative document is:
- `posthumanos_annotated_bibliography.md`

That file should:
- expand the seed source set,
- annotate each item formally,
- tag it by section, program, gap, and stance,
- and begin serving as the master literature bank for the paper.
