# CURRENT PHASE
Repository Bootstrap

# NORTH STAR
Ship a replayable local-first continuity substrate where validator truth survives runtime replacement.

# FROZEN ARCHITECTURAL DECISIONS
1) Validator is canonical.
2) Continuity > execution variance.
3) Canonical and operational state remain separated.
4) Profiles hold strictness; core remains minimal.

# ACTIVE FRONTIERS
Topology freeze, validator spec, replay legality taxonomy, plugin contract model, recovery flows.

# CURRENT IMPLEMENTATION TARGET
Bootstrap governance files are active and canonical.

# NEXT TARGETS
1) Define repository topology manifests.
2) Add validator specifications.
3) Add adversarial replay scenarios.
4) Add continuity/recovery manifests.

# KNOWN CONSTRAINTS
No build step. No framework assumptions. Deterministic local-first execution only.

# ACTIVE RISKS
Session drift, undocumented invariants, canonical/operational bleed, non-admissible runtime shortcuts.

# EXECUTION NOTES
2026-05-13: Bootstrap layer initialized; all future updates are append-only checkpoints.
Software continuity belongs to users through replayable, validator-centered local-first primitives.

# FROZEN ARCHITECTURAL DECISIONS
Validator is canonical. Continuity supersedes runtime variance. Canonical and operational layers remain separated.

# ACTIVE FRONTIERS
Bootstrap governance, topology planning, validator specs, replay scenarios, plugin contracts.

# CURRENT IMPLEMENTATION TARGET
Establish deterministic bootstrap layer: AGENTS.md, .codex/instructions.md, .codex/session.md.

# NEXT TARGETS
Define topology, freeze primitive boundaries, add validator specifications, add adversarial replay scenarios, add continuity manifests.

# KNOWN CONSTRAINTS
No framework assumptions. Local-first execution. Deterministic modifications. Explicit legality boundaries.

# ACTIVE RISKS
Session drift, canonical/operational mixing, undocumented invariants, non-replayable operational shortcuts.

# EXECUTION NOTES
Append-only checkpoint. Update by adding dated entries; do not rewrite prior decisions.
