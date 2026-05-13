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
