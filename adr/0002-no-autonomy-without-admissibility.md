# ADR 0002: No Autonomy Without Admissibility

## Status

Accepted

## Context

AI-mediated systems may generate code, configurations, plans, or probe actions. Direct execution would create unacceptable trust and safety risk.

## Decision

Any machine-state-changing action must pass deterministic admission, sandboxing, proof/checking, or explicit policy validation before execution.

## Consequences

Autonomy is subordinate to admission evidence. Prototype work must define admission classes before executing generated or adaptive actions.
