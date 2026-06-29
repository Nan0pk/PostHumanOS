# PostHumanOS Roadmap

This is the short actionable roadmap. The full R&D plan is in [`research/posthumanos_engineering_roadmap.md`](research/posthumanos_engineering_roadmap.md).

## Current Stage

The project is in **research formalization and repository structuring**. The immediate goal is to make the architecture understandable, decomposable, and ready for bounded prototype work.

## Phase 0 — Formalization

**Primary programs:** A, B, H.

Deliverables:

- formal intent schema v0;
- Universal Capability Contract v0;
- telemetry vocabulary;
- deterministic admission policy v0;
- initial threat model for generated actions and probe actions.

Gate:

- intents are machine-checkable;
- telemetry is normalized or explicitly marked unobservable;
- all planned state-changing actions have admission classes.

## Phase 1 — Modeling and Simulation

**Primary programs:** D, J, with A/B/H support.

Deliverables:

- multi-currency scheduling simulator;
- workload traces or synthetic workload suite;
- provenance graph schema;
- compatibility projection model.

Gate:

- simulator demonstrates energy/latency/thermal/accelerator trade-offs;
- scheduler decisions are explainable through intent, capability, and evidence records.

## Phase 2 — Prototype Wedges

Build five bounded prototypes:

1. telemetry scheduler;
2. UCC parser and capability registry;
3. semantic storage overlay;
4. sandboxed probing emulator;
5. restricted verified code DSL.

Gate:

- at least three wedges meet success criteria;
- all wedges fail safely;
- no wedge bypasses deterministic admission for convenience.

## Phase 3 — Integrated Experimental Platform

Integrate the wedges into an end-to-end runtime loop:

```text
intent → capability/telemetry → plan → admission → execution → semantic/provenance state → audit/rollback
```

Gate:

- end-to-end intent execution works for bounded workloads;
- transition economics are measured;
- provenance supports audit and rollback.

## Phase 4 — Hardware-Coupled Research

Couple the platform to real heterogeneous hardware and privacy-bounded environment/network signals.

Gate:

- real telemetry supports or falsifies UCC assumptions;
- safe-probing remains bounded;
- privacy and policy risks are explicitly controlled.

## Current Priority Tasks

1. Define `intent_schema_v0`.
2. Define `ucc_v0` and example capability contracts.
3. Build a minimal multi-currency scheduler simulator.
4. Define provenance graph node/edge types.
5. Write success metrics for each prototype wedge.

## Not Yet In Scope

- bootable OS images;
- arbitrary hardware fuzzing;
- autonomous Ring 0 execution;
- deletion of filesystems or source code;
- unverified AI-generated machine-state-changing actions.
