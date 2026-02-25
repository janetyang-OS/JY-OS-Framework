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

## Case Index

| Case ID | Case Type | Focus | Codes | Status |
|---|---|---|---|---|
| [case-001](case-001.md) | Transition Trigger | Stability → Level 2 escalation logic | R-COMFORT-1 → FIX-T1 / FIX-E2 / FIX-D1 | Active |

---

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
1) Duplicate the latest case file (or use the template below).
2) Assign the next case id: `case-002`, `case-003`, ...
3) Ensure Evidence Artifact includes at least **1 exact sentence**.
4) Update the Case Index table.
5) Commit with message: `Add case-00X <short title>`
