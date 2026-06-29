# Contributing to PostHumanOS

PostHumanOS is a disciplined systems research program. Contributions should make the architecture clearer, more testable, more grounded, or more buildable.

## Core Contribution Rule

Do not dismiss ambitious ideas as unrealistic. Decompose them into:

- claim type;
- mechanism;
- assumptions;
- dependencies;
- constraints;
- failure modes;
- evidence requirements;
- validation path;
- relation to Programs A–J.

## Claim Register Discipline

When adding or modifying a claim, identify whether it is:

1. metaphor or motivating language;
2. research hypothesis;
3. architectural principle;
4. engineering mechanism;
5. implementation claim;
6. evidence-backed result;
7. open gap.

Do not allow implementation claims to masquerade as established evidence.

## Architectural Invariants

Every contribution must preserve:

- no autonomy without admissibility;
- no abstraction collapse without governance replacement;
- no fluidity without transition economics;
- no physicalism without instrumentation.

## Research Contributions

Research additions should include:

- citation or explicit open-gap marker;
- section/program tags where applicable;
- enabling, foundational, contrasting, or cautionary stance;
- relationship to the existing bibliography and prior-art matrix.

## Engineering Contributions

Engineering additions should include:

- purpose and non-goals;
- dependencies;
- threat/safety assumptions;
- success metrics;
- kill criteria;
- pivot rules;
- test or benchmark plan.

## Terminology Changes

Do not rename core concepts casually. If terminology changes:

1. update [`docs/05_glossary.md`](docs/05_glossary.md);
2. explain why the old term was insufficient;
3. preserve compatibility references where useful.

## AI-Generated Contributions

AI-generated work must follow [`AGENTS.md`](AGENTS.md). In particular, AI-generated code or architecture must not introduce state-changing autonomy without deterministic admission or sandboxing.
