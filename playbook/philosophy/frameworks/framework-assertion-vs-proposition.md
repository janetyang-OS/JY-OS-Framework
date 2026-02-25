# Framework — Assertion vs Proposition

## 1-sentence thesis
A **proposition** is a meaning that can be true or false; an **assertion** is a speaker’s act of committing to a proposition.

---

## Model (Operational)
### Two Layers
1) **Proposition (P)**  
- What is being claimed (content).
- Evaluated by: true / false (or supported / unsupported).

2) **Assertion (A)**  
- The act of stating P as if it’s reliable.
- Evaluated by: responsibility / warrant / evidence discipline.

### Why this matters in the AI era
AI produces propositions at scale.
Humans must decide whether an assertion is justified.

---

## When to use
Use this framework when:
- someone says “AI said it, so it must be true”
- a student gives a correct answer but cannot justify it
- a discussion confuses confidence with evidence

---

## Failure modes (common misapplications)
- **FM1: Treating all propositions as assertions**  
  “If it’s written, it’s committed and reliable.”
- **FM2: Confusing persuasion with warrant**  
  “It sounds logical, so it’s justified.”
- **FM3: Using authority as evidence**  
  “Teacher/AI said so” replaces support.

---

## Bridge-to-Lab (Reading Judgment)
CAP Daily Loop trains the boundary:
- 12 min answering generates a *proposition choice* (option selected)
- 8 min evidence retrieval tests whether you can *warrant an assertion*
- The evidence sentence is the “warrant object”

**Operational rule:**  
No evidence sentence → no justified assertion → `INVALID_FOR_PLAYBOOK`.
