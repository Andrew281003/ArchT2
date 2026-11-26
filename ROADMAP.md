# Roadmap

ArchT2 is experimental. Hardware compatibility remains unverified, and roadmap items are not support or delivery commitments.

> The original project specification containing the ten engineering phases was not accessible from the connected ChatGPT Spaces account when this document was reviewed. The remaining phases are pending that source; this document does not substitute inferred phases for the specification.

## Phase 0 — Project groundwork (current)

- Establish repository governance, security reporting, and licensing.
- Record the target model identifier and define evidence standards for hardware claims.
- Identify research questions and document findings with sources, test conditions, and limitations.
- Define safe test procedures before any hardware experiments.

**Exit criteria:** maintainers can review a scoped, sourced hardware research record and a safety-aware plan for the next phase. No compatibility claim follows automatically.

## Safety requirements

- Do not begin hardware diagnostics or modify macOS, system settings, partitions, or firmware without explicit user instruction.
- Any operation that could erase or overwrite data, alter partitions or boot/security settings, or write firmware requires explicit approval before it is run.
- Use reversible procedures where possible, and record the test conditions, outcome, and limitations.
- Do not redistribute Apple firmware or other proprietary material without verified redistribution rights; preserve third-party licenses and notices.

## Remaining engineering phases

Import the ten phase definitions from the original project specification when that source is available. Until then, do not treat the previous proposed Phase 1–3 descriptions as the authoritative project roadmap.
