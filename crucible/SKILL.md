---
name: crucible
description: Route decision work to the smallest useful Crucible skill. Use when the user asks to think through, stress-test, audit, or finalize a decision and it is unclear whether to use crucible-panel, crucible-grill-me, crucible-grill-you, crucible-escalate, or crucible-decide.
---

Route the decision.

Choose one next move:

- Open question, no fixed plan: use crucible-panel.
- Fixed plan, user wants to answer questions: use crucible-grill-me.
- Fixed plan, user wants no back-and-forth: use crucible-grill-you.
- Final conclusion seems biased or high-stakes: use crucible-escalate.
- User needs the final call: use crucible-decide.

Use at most one next skill unless the user explicitly asks for a full chain.

Do not run a long workflow by default. Pick the smallest useful next move.
