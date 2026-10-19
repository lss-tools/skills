# Brain adaptations: Matt Pocock

Task 1231 adapts the complete selected set, 14 skills and three dependencies.
The original `skills/` tree remains pinned at `49dd158d1076134a641b33efb035946536778336`.
Each adaptation retains its own `LICENSE`, `NOTICE` and `UPSTREAM`.

Brain indexes this directory as optional source `mp`. These skills are addressable:
assign exact names in a Brain task's `скиллы` field and run `start_task.py`.
They do not replace the existing 1C stages or change resident selections.

| Group | Skills |
|---|---|
| Specification and decisions | [mp-grill-with-docs](mp-grill-with-docs/SKILL.md), [mp-triage](mp-triage/SKILL.md), [mp-to-spec](mp-to-spec/SKILL.md), [mp-to-tickets](mp-to-tickets/SKILL.md), [mp-wayfinder](mp-wayfinder/SKILL.md) |
| Engineering | [mp-improve-codebase-architecture](mp-improve-codebase-architecture/SKILL.md), [mp-implement-spec](mp-implement-spec/SKILL.md), [mp-diagnosing-bugs](mp-diagnosing-bugs/SKILL.md), [mp-tdd](mp-tdd/SKILL.md), [mp-retro](mp-retro/SKILL.md) |
| Communication and learning | [mp-handoff](mp-handoff/SKILL.md), [mp-teach](mp-teach/SKILL.md), [mp-wait-what](mp-wait-what/SKILL.md), [mp-writing-for-agents](mp-writing-for-agents/SKILL.md) |
| Dependencies | [mp-grilling](mp-grilling/SKILL.md), [mp-domain-modeling](mp-domain-modeling/SKILL.md), [mp-codebase-design](mp-codebase-design/SKILL.md) |

Cross-source code review uses `ao-code-review-and-quality` from `lss-tools/agent-skills`.
In Brain, resolve its exact canonical path through the skill index.
Updates require a manual comparison with upstream. Brain's `skills-sync` serves the 1C source only.
