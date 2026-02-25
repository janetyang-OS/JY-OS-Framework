# Error Codes (Taxonomy) v0.1

## Purpose
Convert reading mistakes into repeatable diagnosis codes.
Codes must map to fix prescriptions.

---

## Format
- **E-*** = active error (a wrong choice or a broken step)
- **R-*** = risk state (no error today, but instability likely)

Each code includes:
- Definition
- Trigger condition (rule)
- Typical failure pattern

---

## Evidence & Process Errors
### E-EVID-1 — No Evidence Retrieval
**Definition:** Student answers without returning to the text to cite support.
**Trigger:** evidence_sentence missing OR generic (“because it says so”).
**Pattern:** keyword guessing; unstable inference.

### E-EVID-2 — Wrong Evidence Anchor
**Definition:** Evidence sentence cited but does not support the claim.
**Trigger:** evidence contradicts choice OR supports a different option.
**Pattern:** partial-truth traps succeed.

---

## Inference & Scope Errors
### E-INF-1 — Unsupported Leap
**Definition:** Student adds a new idea not stated/implied by the text.
**Trigger:** why includes external knowledge not grounded in passage.
**Pattern:** “sounds right” reasoning.

### E-SCOPE-1 — Extreme Scope Trap
**Definition:** Student selects always/never/only type extremes without proof.
**Trigger:** chosen option contains extreme scope and text does not match.
**Pattern:** overgeneralization.

---

## Reference & Tracking Errors
### E-REF-1 — Pronoun Reference Mis-attach
**Definition:** He/they/it points to wrong person/thing.
**Trigger:** pronoun question wrong OR evidence anchor points to wrong noun.
**Pattern:** competing subjects across sentences.

### E-TIME-1 — Timeline Mis-order
**Definition:** Before/after/when/while sequence misread.
**Trigger:** student’s reason reverses event order.
**Pattern:** multi-layer timeline confusion.

---

## Keyword & Distractor Errors
### E-KEY-1 — Keyword Lock
**Definition:** Student matches a keyword but ignores sentence meaning.
**Trigger:** why repeats keyword but evidence does not logically support.
**Pattern:** distractor uses same vocabulary.

### E-DIST-1 — Partial Truth Acceptance
**Definition:** Option is partly true but not answering the question asked.
**Trigger:** student cites a true detail that doesn’t match the question target.
**Pattern:** “true statement” ≠ “correct answer”.

---

## Risk Codes (No error today)
### R-COMFORT-1 — Comfort Zone Stability (Untested Under Pressure)
**Definition:** High accuracy in same difficulty band; pressure stability unknown.
**Trigger:** ≥3 consecutive sessions ≥90% in same band AND trap density low–med.
**Pattern:** looks stable; may drop under time constraints.

### R-INFER-EDGE — Inference Edge (Near-miss)
**Definition:** Correct answer, but reasoning shows weak evidence alignment.
**Trigger:** score correct but evidence_sentence is vague or borderline relevant.
**Pattern:** future errors likely when traps increase.
