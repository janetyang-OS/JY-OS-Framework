# ⚖️ Principle: The Chain Test (Reality Simulation)
**Status:** System Logic | **Role:** Spec Debugger | **Objective:** Managing Cascading Failures

> "When one missing element kills 7 questions, that’s not a test — that’s a reality simulation."

## 📊 The Failure Map
This diagram illustrates the difference between an independent list of questions and a "Dependency Chain."
![Chain Test Failure](../assets/chain-test-failure.jpg)
*(Fig 1. Q3 Blocked $\rightarrow$ Q4-Q10 Cascading Failure. "One block stops everything.")*

---

## 🔗 The Logic: Serial Dependency
**Context:** An assessment where the *Output* of Q1 becomes the *Input* of Q2.
**The Event:**
* **The Block:** A missing element (e.g., a missing 3D model or reference dot) in Q3.
* **The Result:** **Cascading Failure.** Q4 through Q10 turn grey. You cannot attempt them even if you know the math.

---

## ⚠️ The Critical Distinction: Math vs. Spec
In the AI Era, we must distinguish between two types of errors:

| Error Type | Definition | Consequence | Status |
| :--- | :--- | :--- | :--- |
| **Math Error** | Calculation mistake, Algebra slip. | **Soft Fail.** You can usually continue or get partial credit. | **Fixable** |
| **Spec Error** | Missing data, undefined variable, missing reference. | **Hard Fail.** The system halts. You cannot proceed. | **Fatal** |

> **"Not hard math. Hard spec."**
> The difficulty isn't the calculation; it's the specification.

---

## 🤖 AI Limitation: The "Spec Check"
**The Trap:** Students think "AI is dumb" because it can't solve Q3.
**The Reality:** AI is flagging a **Spec Error**.
* If the prompt lacks the 3D model, the AI *cannot* hallucinate the answer (or it shouldn't).
* **New Skill:** The student must switch from "Solver Mode" to **"Spec Debugging Mode."** (Checking the packet, finding the reference, defining the variable).

---

## 🏗 The Workplace Simulation
This assessment mimics real-world engineering and project management:
1.  **Incomplete Specs:** Requirements are rarely perfect.
2.  **Dependency Chains:** A delay in Phase 1 blocks Phase 2.
3.  **System Repair:** The high-value skill is not "calculating fast," but **"fixing the broken link so the chain can resume."**

### 🛠 The Protocol (Actionable)
* **For Parents:** Don't ask "Did you finish?" Ask **"Is it a Math Error or a Spec Error?"**
* **For Students:** **Spec Check First.** Before calculating, verify that all inputs (Diagrams, References, Definitions) are present.

*Logged by Janet Yang*
*System Dependency Logic - 2026*
