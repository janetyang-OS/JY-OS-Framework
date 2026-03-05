# Protocol Impact Log

This file records **when operational cases lead to protocol updates** in the JY-OS system.

Cases provide the **evidence layer**.  
Protocol updates modify the **operating rules**.

Structure:

case → insight → protocol change

---

## Protocol Impact Records

| Date | Case ID | Insight | Protocol Update |
|-----|-----|-----|-----|
| 2026-02 | case-001 | Stability without pressure testing can create comfort-zone illusion | Introduced Level 2 escalation trigger |
| 2026-03 | case-002 | Students may maintain grammar accuracy but fail reading inference | Added CAP mixed-skill readiness check |
| 2026-03 | case-003 | Single-outcome drift appears in CEFR writing | Introduced FIX-CEFR-SINGLE-OUTCOME |

---

## Impact Categories

### Escalation Rule
Protocol changes that modify **level progression conditions**.

Example:
- Stability → Level 2 transition threshold

### Error Pattern Fix
Protocol updates created to address **repeated error patterns**.

Example:
- tense drift
- inference compression

### Evidence Requirement Update
Rules added to enforce **stronger evidence validation**.

Example:
- mandatory exact sentence extraction

---

## Hard Rule

A protocol change **must reference at least one case**.

If no case exists:

→ mark proposal as `UNVERIFIED`.
