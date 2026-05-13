# EXECUTION MODEL
READ → ANALYZE → PLAN → CONFIRM → MODIFY → VERIFY.

# REPOSITORY DISCOVERY
Enumerate existing topology first. Never fabricate implied folders/files.

# MODIFICATION LAW
- NEVER invent repo structure.
- NEVER claim runtime completeness.
- ALWAYS preserve canonical boundaries.
- ALWAYS separate canonical vs operational.

# CONTINUITY PRESERVATION
Canonical continuity artifacts are append-only replay sources. Optimized runtime state is non-canonical.

# VALIDATOR EXPECTATIONS
Validator admissibility gates canonical mutations. Runtime success without validator legality is failure.

# FILE SYSTEM RULES
Generate deterministic trees. Prefer manifests/schemas/examples over narrative expansion.

# IMPLEMENTATION LOGGING
Record append-only change notes with date, file path, invariant impacted, and validator expectation.

# FAILURE BEHAVIOR
If `AGENTS.md`, `.codex/instructions.md`, or `.codex/session.md` is missing: STOP (`BOOTSTRAP_MISSING`).
