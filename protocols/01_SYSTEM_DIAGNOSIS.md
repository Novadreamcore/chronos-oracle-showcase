# Protocol excerpt 01 — SYSTEM DIAGNOSIS

## Purpose

Test whether a multi-hypothesis research system can keep several software-failure explanations separate and propose small observations that discriminate between them.

## Example benchmark question

A software system shows a visible timer continuing to run while the graphical interface and simulated world occasionally freeze. After several seconds the display may continue. The failure does not always produce an error message.

The research task is to generate **multiple competing failure hypotheses** and propose the smallest useful observations or tests that distinguish them.

## What this benchmark probes

- distinction between UI, simulation and timing paths,
- causal consistency,
- avoidance of invented logs or stack traces,
- whether proposed tests actually discriminate between hypotheses,
- whether a hypothesis contradicts its own actor/liveness assumptions,
- whether reviewer criticism changes later candidates.

## Public boundary

The internal reviewer prompts, scoring logic, regeneration rules and implementation are omitted.
