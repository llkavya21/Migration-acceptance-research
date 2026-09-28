# Technical notes

## Four result states

- `PASS` — evidence supports the scoped requirement.
- `FAIL` — sufficient evidence demonstrates an unapproved violation.
- `UNKNOWN` — evidence is missing, incomplete or ambiguous.
- `APPROVED DIFFERENCE` — a deviation exactly matches an explicit authorized exception with verified compensating behavior.

UNKNOWN and APPROVED DIFFERENCE are intentionally not collapsed into PASS.

## Frozen requirement model

The experiment used exactly 12 business-level acceptance requirement families covering areas including:

- business identity continuity;
- task/project and project/client relationships;
- task responsibility;
- historical approval integrity;
- authorization and access boundaries;
- workflow action capability;
- lifecycle/status meaning;
- required business content.

## Phase 2B — Destination C

Frozen requirements/rules transferred to a different synthetic representation. The AI-assisted blinded review and frozen checker agreed on 48/48 decisions for the four primary reviewed scenarios, but this is **not** a human baseline and does not establish general correctness.

## Phase 3 — Destination D

Destination D was separately authored with disclosed prior-context exposure. Phase 3 reported:

- 12/12 requirements reused unchanged;
- 12/12 rule families reused unchanged;
- destination-specific mapping and adapter work still required;
- 96/96 requirement-level post-reveal adjudications aligned under the frozen scope;
- D-107 remained an explicit out-of-scope coverage gap.

The 96/96 figure is not a pre-authored exhaustive verdict oracle and is not statistical validation.

## Central technical lesson

**Representation reuse is not integration-free.** Reusing frozen business logic still required local identity reconciliation, value mapping, containment traversal, native observations and adapter behavior.
