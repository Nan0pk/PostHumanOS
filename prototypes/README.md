# Prototype Wedges

PostHumanOS should not begin as a full OS rewrite. It should begin as bounded wedges that validate the core mechanisms.

| Prototype | Directory | Main Programs |
|---|---|---|
| Telemetry Scheduler | `telemetry_scheduler/` | B, D, H |
| UCC Parser | `ucc_parser/` | B, J |
| Semantic Storage Overlay | `semantic_storage_overlay/` | F, J, H |
| Sandboxed Probing Emulator | `sandboxed_probe_emulator/` | C, H, B |
| Restricted Verified DSL | `verified_dsl/` | G, H, A |

Each prototype must include purpose, non-goals, inputs, outputs, success metrics, kill criteria, pivot rules, and safety assumptions.
