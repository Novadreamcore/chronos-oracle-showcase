# CHRONOS ORACLE — Public checkpoint notes

This file documents only selected public-facing checkpoints. It is not a complete internal development history.

## Alpha 0.3.85 — BUGFIX / UX CHECKPOINT

- current documented application checkpoint,
- Run History layout hardened for smaller displays,
- `CONTINUE FROM HERE` workflow corrected so the selected ThoughtStream target is preserved,
- clearer custom ThoughtStream target editing,
- clearer view-only clearing behavior,
- result export workflow consolidated,
- dedicated Synaptikon STOP control,
- RCMS LIVE activity visualization added,
- Institute file loading added with provenance retained,
- Synaptikon reporting clarified so model rationale and later final guard/override reasoning are not conflated,
- September 2026 exploratory ThoughtStream series documented,
- refreshed public DreamCore screenshot for the Alpha 0.3.85 interface,
- added the first public Synaptikon screenshot, including the current Run History surface.

Public examples: `protocols/04_THOUGHTSTREAM_ATTRACTOR_EXAMPLES.md`.

## Alpha 0.3.84 — WORKFLOW UI

- Run History integrated into the workbench,
- navigation back into prior module runs,
- `CONTINUE FROM HERE` workflow,
- expanded Synaptikon Top-N / inspector workflow,
- workbench consolidated around ORACLE / ThoughtStream / DreamCore / Institute / Synaptikon.

Intermediate revisions between 0.3.67 and 0.3.84 are intentionally not reconstructed here when exact public deltas are unavailable.

## Alpha 0.3.67 — DREAMCORE STATUS + TXT EXPORT

- DreamCore status visibility in the integrated workbench
- TXT export for DreamCore output
- previous documented application checkpoint

## Alpha 0.3.66 — INSTITUTE RESULTS FOLDER

- dedicated Institute results-folder handling
- clearer separation of Institute review output from other runtime material

## Alpha 0.3.65 — INDEPENDENT CONTROL

Introduced explicit ThoughtStream comparison modes:

- **A0 FREE**
- **NR CONTROL**
- **B0 GUARDED**

NR CONTROL receives the original prompt on every tick and does not receive the previous generated thought as the next input.

## Alpha 0.3.64 — UI EXPORT

- ThoughtStream / UI export functionality

## Alpha 0.3.63 — NEW STREAM RESET

- explicit reset behavior for starting a new stream

## Alpha 0.3.62 — THOUGHTSTREAM AUTO-LIMIT

- automatic ThoughtStream run limiting
