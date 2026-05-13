# EXECUTION MODEL
Deterministic agent execution: discover, validate, modify minimally, verify, log.

# REPOSITORY DISCOVERY
Inspect existing topology before edits. Never invent missing structure without explicit creation steps.

# MODIFICATION LAW
NEVER invent repo structure. NEVER claim runtime completeness. ALWAYS preserve canonical boundaries. ALWAYS separate canonical vs operational.

# CONTINUITY PRESERVATION
Treat continuity artifacts as append-only sources of replay truth. Prefer manifests and schemas over descriptive prose.

# VALIDATOR EXPECTATIONS
All canonical mutations must remain validator-admissible. Runtime shortcuts cannot redefine continuity truth.

# FILE SYSTEM RULES
ALWAYS generate deterministic file trees. ALWAYS prefer manifests over prose. Do not introduce framework or build-step assumptions.

# IMPLEMENTATION LOGGING
ALWAYS write append-only implementation logs with concrete file paths and rationale.

# FAILURE BEHAVIOR
STOP execution if bootstrap missing. Stop when invariants conflict or legality is unclear.
