# Philosophy Playbook (PVUL)

## Purpose
In JY-OS, philosophy is not content consumption.
It is a **validated understanding system**.

Core operating chain:
**input → model → practice → student output → diagnosis → fix → assetization**

This module exists to:
- prevent “answer dependency” in the AI era
- train evidence-based reasoning and self-correction
- generate reusable worldview assets (frameworks, glossary, cases)

---

## Core Loop: PVUL (Philosophy Validated Understanding Loop)
PVUL is the standard workflow used after watching a philosophy video or reading a concept.

Reference:
- [➡️ PVUL Loop Doc](bridge-to-lab/philosophy-validated-understanding-loop.md)

---

## What Counts as Evidence (in Philosophy)
Philosophy evidence is not “a correct opinion.”
Evidence is a **checkable output**:

Minimum capture fields:
- student_claim (verbatim)
- student_reason (verbatim)
- student_counter_check (verbatim)
- failure_mode (if any)

No output → no evidence → no asset.

---

## Artifacts (GitHub Asset Types)
## Key References
- Framework Library Index  
  [➡️ Open Doc](frameworks/index.md)

- Glossary  
  [➡️ Open Doc](glossary.md)

- Positioning Snippet  
  [➡️ Open Doc](positioning/why-philosophy-in-ai-age.md)

Each PVUL cycle must produce **at least one** artifact.

Choose ONE per cycle:
1) **Framework Page** (model + use cases + failure modes)  
   Path: `frameworks/framework-<topic>.md`

2) **Glossary Update** (3 terms)  
   Path: `glossary.md`

3) **Positioning Snippet** (claim + anti-misunderstanding list)  
   Path: `positioning/<topic>.md`

4) **Bridge-to-Lab Note** (how this concept supports CAP judgment workflow)  
   Path: `bridge-to-lab/<topic>.md`

5) **Case Entry** (anonymized student understanding check)  
   Path: `case-library/philo-case-###.md`

6) **Changelog Update** (weekly worldview rules)  
   Path: `../CHANGELOG.md`

Hard rule:
If no artifact is produced → `INVALID_FOR_PLAYBOOK`.

---

## Case Creation (Philosophy)
We do NOT archive every PVUL session.
We create a philosophy case when:

Case triggers:
- repeated misunderstanding persists 2+ cycles
- a concept becomes a “core worldview rule” used across modules
- the student output clearly shows a reasoning failure mode (jump / misapply)

Recommended case format:
- context
- concept + model
- student output evidence
- diagnosis code + trigger condition
- fix prescription + next test

---

## Diagnosis & Fix (Lightweight)
Philosophy diagnosis focuses on understanding stability, not writing quality.

Suggested diagnosis codes (optional):
- U1: recall only
- U2: partial application
- U3: stable understanding
- R-JUMP: reasoning jump
- R-MISAPPLY: model misapplied

Prescription:
- micro-step fixes only (restate claim, force counterexample first, limit reasoning chain)

(If needed, we can formalize these into `taxonomy/` later.)

---

## Link to Reading Judgment Playbook
Philosophy supports Reading Judgment by training:
- evidence discipline (citation mindset)
- inference control (bounded reasoning)
- self-correction (counter-check reflex)

Bridge notes live here:
- [➡️ Bridge-to-Lab](bridge-to-lab/)

---

## Non-Negotiables
1) Philosophy outputs must be **checkable** (claim/reason/counter-check).
2) One artifact per PVUL cycle (minimum).
3) Keep work minimal: 1 model + 1 output snapshot is enough.
4) No motivational fluff; only operational clarity.
