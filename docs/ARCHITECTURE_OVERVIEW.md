# Architecture overview — public level

This document deliberately describes CHRONOS only at a **high level**.

A typical conceptual flow is:

`QUESTION → INTAKE → ROUTER → EVIDENCE → HYPOTHESES → INSPECTOR → SANITY → ADVERSARY → REFLECTION → SYNTHESIS → FINAL AUDIT`

## Why multiple stages?

Different errors require different kinds of pressure.

A hypothesis may be:

- internally inconsistent,
- unsupported by supplied evidence,
- numerically implausible,
- causally impossible,
- dependent on an invented observation,
- technically possible but not discriminative,
- able to survive one reviewer while failing another.

Keeping the stages distinct creates a visible trail of where a claim entered, where it was challenged and whether it remained eligible for synthesis.

## Intentionally omitted from this public document

The showcase does **not** publish:

- exact system prompts,
- exact scoring rules,
- private thresholds,
- source-selection implementation,
- internal retry/regeneration logic,
- model routing details,
- source code.

Those remain part of the private research and implementation repository.
