# System Failure Patterns — v1.0

## Scope
This document defines recurring failure modes observed in the Reading Judgment Lab,
and the corresponding detection signals and control actions.

---

## Pattern 01 — Signal vs Perception Mismatch

### Definition
A failure condition where:

- system-level learning signals indicate improvement
- external perception (parent/student) does not recognize improvement

---

### Detection Signals

At least TWO of the following:

- measurable improvement in structure / consistency / control (signal ↑)
- parent reports “no visible improvement”
- increased student complaints
- requests to reduce difficulty or “stress”
- increased parental involvement in teaching direction

---

### Root Cause

Misalignment between two evaluation systems:

**System Evaluation**
- tracks internal skill development (structure, consistency, control)
- detects early-stage (invisible) improvement

**Perception Evaluation**
- focuses on visible output and emotional experience
- expects immediate, observable results

---

### Failure Mechanism

1. improvement occurs at structural level (not yet visible)
2. perception does not detect change
3. perception overrides system judgment
4. execution consistency drops or program is terminated

---

### Risk Signals

- R-SIGNAL-PERCEPTION-MISMATCH
- R-PARENT-INTERVENTION-CONFLICT
- R-EXECUTION-INCONSISTENCY

---

### Impact

- learning progression may be present but unrecognized
- execution stability decreases
- system continuity breaks prematurely

---

### Control Actions

**1. Visibility Layer (mandatory)**
- provide concrete before/after examples
- highlight 1–2 observable improvements per week
- avoid abstract explanations

**2. Expectation Alignment (early stage)**
- explicitly communicate:
  “early improvement may not be immediately visible”
- define what “improvement” looks like at each stage

**3. Execution Protection**
- enforce minimum execution threshold (≥4 sessions/week)
- do not adjust core training structure based on perception alone

**4. Communication Rule**
- separate:
  - signal (data)
  - interpretation (explanation)
- avoid mixing them in reporting

---

### Non-Negotiable Rule

If execution consistency is broken:

→ system output is no longer valid  
→ progression cannot be evaluated  

---

### Reference Case

- case-008-signal-perception-mismatch.md

---

## Pattern Framework

All system failure patterns must define:

1. Definition  
2. Detection Signals  
3. Root Cause  
4. Failure Mechanism  
5. Risk Signals  
6. Impact  
7. Control Actions  

---

## Next Patterns (To Be Added)

- Execution Drop Pattern
- Overconfidence Pattern
- Parent Control Override Pattern
