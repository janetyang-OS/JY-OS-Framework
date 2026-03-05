# Judgment Protocol Layer (CAP Reading) — v0.1

## Definition
**Judgment Protocol Layer = a verifiable, repeatable decision procedure** for CAP reading.

It specifies *how decisions are made* during reading, independent of:
- topic familiarity
- keyword matching habits
- brute-force practice volume

This layer turns “reading performance” into an **auditable reasoning process**:

**input → evidence → exclusion → claim → validation**

---

## Relationship to the Playbook Loop
- **Reading Judgment Playbook (12+8 SOP)** defines *how practice runs* (workflow + evidence artifacts).
- **Judgment Protocol Layer** defines *how answers are judged* (decision algorithm).
- **Taxonomy** provides diagnostic labels (`E-*`, `R-*`) and fixes (`FIX-*`).
- **Case Library** stores curated proof of change (pattern → intervention → outcome).

If you want to know “what to do daily,” go here:  
- [➡️ Reading Judgment Playbook](../README.md)

If you want to know “how judgment is constructed,” you are here.

---

## Protocol Operating Rules (Non-Negotiables)
1) **No answer reveal during the 12-minute phase.**
2) Every judged answer must be backed by **one exact evidence sentence** (when applicable).
3) A choice is only “valid” if it passes:
   - **evidence support**
   - **scope correctness**
   - **logic direction**
4) If no error occurs, assign a **risk code** (`R-*`).  
5) Prescriptions must be **1–2 fixes with dose** (from Fix Library).

If evidence is missing → mark: `INVALID_FOR_PLAYBOOK`.

---

## The Three Protocol Clusters
This v0.1 layer is organized as three clusters.  
Each cluster is a **reasoning filter**, not a “skill topic.”

### Cluster A — Scope & Transition Control
Goal: prevent “almost correct” choices caused by **quantifier drift** or **turning-point blindness**.

Typical failures:
- “Some” → “Most” overreach
- missing `however / although` flip
- partial-truth traps

Protocols:
- [➡️ Cluster A README](cluster-a-scope-transition/README.md)
- `scope-control-protocol.md`
- `transition-sensitivity-protocol.md`

---

### Cluster B — Evidence Validation System
Goal: replace intuition guessing with **text-grounded validation**.

Typical failures:
- selecting by similarity (“looks like the passage”)
- evidence supports only *part* of the claim
- local detail correct but global intention wrong

Protocols:
- [➡️ Cluster B README](cluster-b-evidence-validation/README.md)
- `evidence-locator-protocol.md`
- `local-vs-global-protocol.md`
- `inference-integration-protocol.md`

---

### Cluster C — Information Alignment
Goal: handle CAP’s increasing use of **mixed-format inputs** and **execution constraints**.

Typical failures:
- chart/table/map + text misalignment
- combining wrong dimensions (who/when/where)
- time collapse: stuck on one passage → whole section fails

Protocols:
- [➡️ Cluster C README](cluster-c-information-alignment/README.md)
- `non-continuous-text-protocol.md`
- `time-distribution-protocol.md`

---

## Protocol Output Format (Minimal, Auditable)
When applying any protocol, the minimum record for one question is:

- `q_type`
- `chosen_option`
- `claim` (what the option asserts)
- `evidence_sentence (EXACT)`
- `validation`
  - `scope_check`: PASS/FAIL + why
  - `direction_check`: PASS/FAIL + why
  - `exclusion`: at least 1 eliminated option + reason
- `diagnosis_code`: `E-*` or `R-*`
- `prescription`: `FIX-*` with dose (if needed)

This format is designed to be:
- human-executable
- AI-executable
- coach-auditable

---

## Integration With Taxonomy
Diagnosis:
- [➡️ Error Codes](../../taxonomy/error-codes.md)

Prescription:
- [➡️ Fix Library](../../taxonomy/fix-library.md)

---

## Versioning
- v0.1 = initial clustering + minimal protocol interface
- Future versions will add:
  - protocol checkpoints by question type
  - standard “trap patterns” library
  - scoring rubric for evidence quality

Track upgrades in:
- [➡️ Playbook CHANGELOG](../../CHANGELOG.md)
