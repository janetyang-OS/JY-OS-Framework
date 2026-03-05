# Case Taxonomy

This file defines the classification system for all cases in the Case Library.

Cases document **learning behavior patterns**, which fall into several recurring categories.

The taxonomy helps:

- track recurring error families
- identify protocol escalation triggers
- analyze learning system performance

---

# 1. Case Type

Every case must belong to one of three types.

| Type | Meaning |
|-----|------|
| Error Pattern | Recurring learning error or instability |
| Risk Trigger | Stability risk detected before escalation |
| Transition Trigger | Level escalation event |
| Skill Transition | Student moving between competence bands |
| Protocol Evolution | Case caused system rule change |

---

# 2. Error Family Codes

Error cases are categorized into families.

## Reading Judgment

| Code | Meaning |
|-----|------|
| E-INFER | Inference reasoning failure |
| E-EVID | Evidence misalignment |
| E-KEY | Keyword lock (surface reading) |
| E-SCOPE | Scope mismatch |

---

## Grammar / Language Control

| Code | Meaning |
|-----|------|
| WR-TENSE | Tense instability |
| WR-TENSE_SEQ | Past sequence confusion |
| WR-CONJ | Connector misuse |
| WR-AGREE | Agreement error |

---

## Writing Structure

| Code | Meaning |
|-----|------|
| ARG-LAYER | Missing argument layers |
| ARG-CONTRA | Missing counterargument |
| ARG-CONCL | Weak conclusion |

---

# 3. Risk Codes

Risk codes mark **potential instability** even when errors are not present.

| Code | Meaning |
|-----|------|
| R-COMFORT | Comfort-zone stability |
| R-DUAL-SUPPORT | Multiple plausible answer trap |
| R-TIME-PRESSURE | Performance drops under time constraint |

---

# 4. Fix Codes

Fix codes define **intervention protocols**.

Each fix must include a **dose**.

Example format:

Examples:

| Fix Code | Purpose |
|------|------|
| FIX-T1 | Timed escalation test |
| FIX-E2 | Evidence retrieval enforcement |
| FIX-D1 | Distractor elimination training |
| FIX-CEFR-TENSE | Narrative tense stability |
| FIX-CEFR-SINGLE-OUTCOME | Single-result discipline |

---

# 5. Case Tagging Rule

Each case should include at least:

- 1 Case Type
- 1 Error Code OR 1 Risk Code
- 1 Fix Code

Example:

---

# 6. Future Use

This taxonomy allows future analysis such as:

- most common error family
- protocol effectiveness
- learning progression patterns

The taxonomy evolves as the system grows.
