# Case Library (Anonymized)

## Purpose
This library stores **Case Units** that document real operational casework:

**workflow → evidence → diagnosis → prescription → change**

Cases are anonymized and written to be **repeatable**: another coach should be able to execute the same prescription.

---

## How to Use This Library
- Use cases as pattern references for:
  - onboarding / intake diagnosis
  - escalation triggers (level-up decisions)
  - fixing recurring error families
  - training new coaches to follow the same workflow

---

## Weekly Update Workflow

New cases are added **every Friday** based on AI Coach weekly reports.

Each report may generate multiple Case Units (one per student or event).

### Workflow

1. AI Coach weekly reports collected
2. Extract key signals:
   - error pattern OR risk trigger
   - supporting evidence sentence
   - diagnosis codes
3. Convert to Case Unit format
4. Assign next Case ID
5. Update Case Index
6. Commit

### Typical Weekly Additions
A single weekly report cycle may add **3–6 new cases**.

These cases document:

- reasoning error patterns
- stability triggers
- escalation logic
- protocol improvement signals

## Case Index

| Case ID | Case Type | Focus | Codes | Status |
|---|---|---|---|---|
| [case-001](case-001.md) | Transition Trigger | Stability → Level 2 escalation logic | R-COMFORT-1 → FIX-T1 / FIX-E2 / FIX-D1 | Active |
| case-002 | Error Pattern | CEFR writing single-outcome drift | FIX-CEFR-SINGLE-OUTCOME | Active |
| case-003 | Error Pattern | CAP grammar trap cluster (tense sequence / warning connector) | FIX-WR-TENSE_SEQ / FIX-WR-CONJ_WARN | Active |
| case-004 | Skill Transition | B1 → B2 argument structure gap | B2-ARG-GATE | Active |
| case-005 | Risk Trigger | Dual-support evidence discrimination | R-DUAL-SUPPORT-GATE | Active |
| case-006 | Error Pattern | Narrative tense consistency | FIX-CEFR-TENSE | Active |

---

## Case Categories

Cases fall into three operational categories.

### 1️⃣ Error Case
Documents a recurring reasoning or language error pattern.

Example:
- inference compression
- evidence misalignment
- tense consistency drift

### 2️⃣ Transition Trigger
Documents a **protocol escalation event**.

Example:
- stability → timed pressure test
- Level 1 → Level 2 CAP transition

### 3️⃣ Protocol Evolution
Documents situations where **a protocol rule changes** due to repeated cases.

Example:
- new evidence verification rule
- modified escalation threshold

## Case Unit Format (Standard)

Every case file must include:

1) **Context**  
2) **Material**  
3) **Outcome (Performance Log)**  
4) **Evidence Artifact** *(exact sentence required)*  
5) **Diagnosis** *(error codes OR risk code + trigger condition)*  
6) **Prescription** *(fix codes with dose)*  
7) **Follow-Up Plan**  

---

## Hard Rules
1) **Evidence sentence cannot be empty.**  
   If missing → mark `INVALID_FOR_PLAYBOOK`.

2) If **no error codes**, a **risk code is required**.

3) Fix codes must include **dose** (time / #questions / evidence requirement).

4) Keep cases anonymized:
- Use `student_id` like `G7-BEAR-01`
- Do not include names, schools, or identifiable details

---

## Add a New Case (Quick Steps)

1. Duplicate the latest case file or use `case-template.md`.
2. Assign the next Case ID: `case-002`, `case-003`, ...
3. Ensure **Evidence Artifact includes at least 1 exact sentence**.
4. Confirm either:
   - error codes exist, OR
   - a risk code is assigned.
5. Add the case to the **Case Index table**.
6. Commit with message:

Add case-00X <short-title>
