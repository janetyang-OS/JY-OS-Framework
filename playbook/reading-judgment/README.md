# Reading Judgment Playbook (CAP)

## Purpose
This module rebuilds reading performance by replacing intuition guessing with a repeatable workflow:

**workflow → evidence → diagnosis → prescription → change**

This is not “more practice.”
It is **judgment reconstruction**.

---

## The Core Loop (Daily 20-Minute SOP)

### ⏱️ 12 minutes — Answer (No answer-checking)
Rules:
- Answer all questions within 12 minutes.
- Do not look up answers.
- Do not ask for hints.
- If uncertain, choose the best option **but mark the uncertainty**.

Output required (per question):
- `chosen_option`
- `why` (1–2 sentences)

### ⏱️ 8 minutes — Evidence Retrieval
Rules:
- Return to the passage.
- Find **one exact sentence** that supports the chosen option.
- Copy it as the evidence sentence.

Output required (minimum 1 item per day):
- `q_type`
- `student_why`
- `evidence_sentence (EXACT)`

Hard rule:
If evidence sentence is missing → `INVALID_FOR_PLAYBOOK`.

---

## What We Track (Minimal Metrics)
Daily:
- Score (optional)
- Evidence Artifact quality (required)
- Diagnosis codes (error OR risk)

Weekly:
- Error recurrence rate (same code repeating)
- Evidence hit rate (does evidence truly support the claim?)
- Stability under constraint (timed sets / trap density)

---

## Diagnosis → Prescription Engine

### Diagnosis (Taxonomy)
Use:
- `E-*` codes for active errors
- `R-*` codes for risk states (no error today)

Reference:
- [➡️ Error Codes](../taxonomy/error-codes.md)

### Prescription (Fix Library)
- Assign **1–2 fixes only**
- Fixes must include **dose**
  - time / #questions / evidence requirement

Reference:
- [➡️ Fix Library](../taxonomy/fix-library.md)

---

## Daily Log → Case Unit (How Assets Are Created)

### Daily Log (lightweight)
Store a daily record using:
- [➡️ Case Record Schema](../case-library/case-record-schema.md)

### Case Unit (curated)
We do NOT publish every daily log.
We curate cases when a pattern appears:

Case triggers (examples):
- a recurring error persists 3+ times
- a stable student needs escalation testing
- a fix clearly reduces recurrence

Case storage:
- [➡️ Case Library](../case-library/README.md)

---

## Escalation Rules (When to Level Up)

### Level 1 → Level 2 (Transition Trigger)
Use a risk-based trigger when performance is stable but untested.

Example:
- `R-COMFORT-1`  
  ≥3 consecutive sessions ≥90% in same difficulty band AND trap density low–med  
  → introduce mild pressure tests

Typical prescriptions:
- `FIX-T1` timed set + evidence retrieval
- `FIX-E2` strict evidence citation
- `FIX-D1` partial-truth filter

---

## Non-Negotiables (System Rules)
1) **Do not reveal answers immediately.**
2) **Evidence sentence is mandatory** (minimum 1 per session).
3) If no error codes, assign a **risk code**.
4) Fixes must include **dose**.
5) Keep the loop small: we optimize stability, not volume.

---

## Output Standards (for Coaches)
A valid daily report must include:
- Outcome snapshot (score + skill notes)
- 1 evidence artifact (exact sentence)
- Diagnosis code(s)
- 1–2 fix prescriptions (with dose)
- Next-step focus (1 line)

If missing evidence sentence → mark `INVALID_FOR_PLAYBOOK`.
