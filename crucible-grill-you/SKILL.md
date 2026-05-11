---
name: crucible-grill-you
description: Use when there is already a plan and the user wants the agent to stress-test it without back-and-forth. The agent interrogates its own plan, revises it, and returns the smallest stronger version.
---

Grill your own plan.

Ask up to five hard questions. Each question must target something that could break the plan:

- hidden assumption
- missing dependency
- edge case
- evidence gap
- simpler alternative

For each question, answer:

- Skeptic:
- Answer:
- Change to plan:

If a question can be answered by reading code or files, inspect them instead of guessing.

Stop when no new hard question remains.

Return only:

- Original weak point:
- Changes made:
- Remaining risk:
- Stronger plan:
- Smallest verification:
