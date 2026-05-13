# ZAYVORA COOKBOOK

## WHAT THIS REPO IS
Continuity runtime substrate.
- Zayvora: authority + replay + orchestration base layer.
- Alchemist: session/content engine on top of continuity primitives.
- Daxini: distribution/economy layer constrained by continuity legality.

## WHAT THIS REPO IS NOT
Not chatbot software. Not SaaS onboarding. Not dashboard glue. Not AI-wrapper UX.

## CONTINUITY LAW
Canonical continuity is append-only and replay-recoverable. Any mutation that cannot re-derive authority lineage is illegal.

## VALIDATOR FIRST
Validator defines continuity truth. Runtimes are replaceable executors.

## CANONICAL VS OPERATIONAL
Canonical: admissible, replayable, portable, hash-stable.
Operational: cache/index/runtime optimization; disposable and re-derivable.

## REPO EXECUTION RULES
1) Read target files fully before editing.
2) Prefer manifests/schemas/traces over prose.
3) Keep canonical and operational artifacts separated.
4) Write deterministic topology changes only.

## PLUGIN PHILOSOPHY
Plugin boundaries are contract-first: inputs, outputs, legality scope, replay impact. Core must not hardcode ecosystem behavior.

## FILE CREATION RULES
Create new files only for primitives, validators, manifests, replay scenarios, recovery flows, or plugin contracts.

## README RULES
Start with system problem, then invariants, primitives, boundaries, legality/recovery semantics, canonical/operational split, failure/replay behavior, and extensibility.

## ARCHITECTURAL INVARIANTS
Validator canonicality. Continuity over execution. Local-first persistence. Explicit lineage. Recoverability under divergence.

## FORBIDDEN PATTERNS
Hidden mutable state, cloud-required control planes, framework lock-in, non-replayable side effects, marketing copy.

## FUTURE DIRECTION
Target topology primitives: `/validator`, `/continuity`, `/authority`, `/runtime`, `/manifests`, `/replay`, `/scenarios`, `/recovery`, `/plugins`, `/workstations`, `/profiles`, `/storage`, `/examples`, `/cea`.
A continuity-runtime substrate for local-first personal software. It defines replayable primitives, validator contracts, legality boundaries, and plugin-capable orchestration.

## WHAT THIS REPO IS NOT
Not a chatbot, SaaS dashboard, AI wrapper, growth funnel, or productivity app shell.

## CONTINUITY LAW
All canonical state must be reconstructible from append-only continuity artifacts. If replay cannot recover authority, the change is invalid.

## VALIDATOR FIRST
Validator outputs are canonical truth. Runtime execution is admissible only when validator legality checks pass.

## CANONICAL VS OPERATIONAL
Canonical: replayable, portable, hash-stable, admissible. Operational: optimized, runtime-local, replaceable caches and indexes.

## REPO EXECUTION RULES
Read full target files before edits. Preserve deterministic file trees. Never mutate canonical history in place. Prefer manifests, schemas, traces, and validator outputs over narrative prose.

## PLUGIN PHILOSOPHY
Plugins are first-class boundaries with explicit contracts, legality scopes, and replay implications. Ecosystem growth must not require core rewrites.

## FILE CREATION RULES
Create files only when they establish missing primitives, manifests, validators, scenarios, or recovery flows. New topology must be explicit and deterministic.

## README RULES
Start with system problem, then invariants, primitives, boundaries, legality/recovery semantics, canonical/operational separation, failure modes, replay semantics, and extensibility.

## ARCHITECTURAL INVARIANTS
Continuity over execution. Validator over runtime. Local-first persistence. Explicit authority lineage. Recoverability under partial failure.

## FORBIDDEN PATTERNS
Hidden mutable state, cloud-required assumptions, framework lock-in, magical abstractions, unverifiable side effects, and marketing-style copy.

## FUTURE DIRECTION
Evolve toward a continuity runtime ecosystem: validator specifications, replay scenarios, manifest taxonomies, plugin contracts, workstation primitives, and recovery tooling.
