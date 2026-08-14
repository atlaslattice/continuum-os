# Alexandria 2.0 Public Canon

This repository is the public-facing gateway to the Atlas Lattice / Alexandria 2.0 corpus.

## Canon rule

Git history preserves what was published. Canon status describes how an artifact should be interpreted now. Nothing is silently promoted from assertion to fact, and nothing is silently erased because it was later revised.

Every canonical artifact should be addressable by:

- stable repository/path identity
- provenance and revision history
- evidence/status class
- 12 Houses × 12 Spheres placement or relationships
- program/project relationships
- release state

## Evidence and status classes

| Class | Meaning |
|---|---|
| `MEASURED` | Direct experimental, observational, or field measurement with source data/provenance |
| `DERIVED` | Calculation or conclusion derived from stated inputs |
| `SIMULATED` | Computational/model output; not a physical measurement |
| `PROPOSED` | Engineering, governance, or systems design proposed for evaluation/build |
| `HYPOTHETICAL` | Unverified mechanism or explanatory hypothesis |
| `HISTORICAL` | Preserved earlier state, superseded design, or development record |
| `REFERENCE` | External/upstream material retained for study, interoperability, or provenance |
| `QUARANTINED` | Preserved but excluded from active canonical retrieval/build paths pending review |

A document may contain claims with different classes. Claim-level classification takes precedence over document-level shorthand.

## Canonical invariants

1. **Source is not interpretation.** Preserve originals and their history.
2. **Assertion is not fact.** Claims retain evidence state.
3. **Simulation is not measurement.** Never collapse the distinction.
4. **Provenance is additive.** Corrections supersede; they do not rewrite history.
5. **Upstream stays upstream.** Forks retain original authorship, license, history, and attribution.
6. **Quarantine preserves.** Exclusion from active use does not require deletion.
7. **The 12×12 is a view, not a folder tree.** Artifacts may relate to multiple Houses/Spheres simultaneously.
8. **Quantities carry units and conditions.** Important numbers should be machine-checkable wherever possible.
9. **Public canon must be reproducible.** A reader should be able to trace a claim to its source or see clearly that it is proposed/hypothetical.
10. **Nothing promotes itself.** Promotion of evidence/release state requires an explicit reviewed change.

## Relationship to the source corpus

The public GitHub corpus is treated as the durable public receipt and source layer. Alexandria 2.0 may render many views over that corpus — project, sphere, evidence, timeline, geography, provenance, infrastructure node — without moving or rewriting the underlying source repositories.

## Active public entry points

- `atlas-lattice-foundation` — architecture, specifications, governance and 144-Sphere material
- `open-regenerative-compute-standard` — regenerative compute standard and evidence-oriented implementation material
- `uws` — universal workspace command surface / Aluminum lineage
- `sheldonbrain-rag-api` — persistent-memory and retrieval infrastructure
- `constitutional-os` / `constitutional-continuum` — governance and constitutional system work
- `manus-artifacts` — generated artifacts and supporting material; individual artifacts retain their own status

## Public-library rule

Restored upstream forks and reference repositories are part of the Alexandria Library, not automatically Atlas-authored projects. Their presence supports reproducibility, learning, interoperability, and archival access while preserving upstream attribution.
