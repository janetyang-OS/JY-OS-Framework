# Case Record Schema (Playbook Standard)

## Purpose
Standardize daily logs and case entries so they can be aggregated into:
workflow → evidence → diagnosis → prescription → change.

This schema is intentionally minimal to avoid documentation overload.

---

## Entity Types
### 1) Daily Log (per session)
A lightweight record used for weekly reporting and trend tracking.

### 2) Case Unit (anonymized)
A curated snapshot used for the public/private case library.

---

## A) Daily Log — Required Fields

### Identification
- `student_id` (anonymized): e.g., `G7-BEAR-01`
- `date` (YYYY-MM-DD)
- `program` (CAP / PVUL)
- `grade_band` (e.g., G7)
- `school_type` (Public / Private / International)

### Material
- `text_id` (optional but recommended)
- `topic`
- `difficulty_band` (L1 / L2 / L3 or your internal label)
- `trap_density` (Low / Medium / High)

### Outcome
- `score_raw` (e.g., 5/5)
- `main_idea` (OK / Risk / Fail)
- `detail_tracking` (OK / Risk / Fail)
- `inference_control` (OK / Risk / Fail)
- `distractor_elimination` (OK / Risk / Fail)

### Evidence Artifact (minimum 1 item)
- `q_type` (Main idea / Detail / Inference / Reference / Time)
- `student_why` (verbatim or close paraphrase)
- `evidence_sentence` (EXACT quote from passage)

### Diagnosis → Prescription
- `error_codes` (0–3 max)
- `risk_code` (required if no error code)
- `trigger_condition` (1 sentence rule)
- `fix_codes` (1–2 max, with dose)

### Follow-up
- `next_focus` (what to test tomorrow)
- `notes` (optional, 2 lines max)

---

## B) Case Unit — Required Fields (GitHub Case Library)

- `case_id`: `case-###`
- `title`
- `case_type`: (Recovery / Transition Trigger / Stability Proof)
- `context` (student profile + goal)
- `material` (topic + structure + load)
- `outcome` (performance log + pattern)
- `evidence_artifact` (1–2 items, exact sentences required)
- `diagnosis` (error/risk code + trigger condition)
- `prescription` (fix codes with dose)
- `follow_up_plan` (what changes to observe)

---

## Hard Rules
1) Evidence sentence cannot be empty. If missing → `INVALID_FOR_PLAYBOOK`.
2) If no error codes, a risk code is required.
3) Fix codes must include dose (time / #questions / evidence requirement).
