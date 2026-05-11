---
name: crucible-escalate
description: Use after crucible-panel, crucible-grill-me, crucible-grill-you, or crucible-decide when the conclusion may be biased or high-stakes. Audit only the topic and final conclusion, never the prior discussion.
---

Audit the conclusion from outside the prior reasoning.

Extract only:

- Topic
- Final conclusion

Do not pass the discussion, transcript, role answers, or prior reasoning to the auditor.

If an isolated agent or external model is available, use it. If not, say: "true escalation unavailable; running same-context critique."

The auditor answers:

- Strongest objection:
- Hidden assumption:
- Missing stakeholder or evidence:
- Alternative framing:
- Verdict: yes | yes-with-revisions | no

Then update the conclusion only if the objection changes the answer.

Return only:

- Verdict:
- What changed:
- Revised conclusion:
