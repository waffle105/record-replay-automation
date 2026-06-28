---
name: record-replay-automation
description: "Design and validate record-and-replay computer automations. Use when a task is UI-based, has no API, follows a fixed path, repeats often, and needs Codex or Computer Use to learn from a demonstrated workflow while keeping risky steps human-confirmed."
---

# Record Replay Automation

Use this workflow when the user wants Codex to learn a repeated UI task.

## Suitability Check
- The task happens in a visible app or webpage.
- There is no reliable API or batch import/export.
- The path is mostly fixed.
- It repeats enough to justify automation.
- Mistakes are low-risk or can be caught before final submission.

## Workflow
1. Run the suitability check before recording.
2. Ask the user to demonstrate one clean example if needed.
3. Summarize the goal, steps, fields, success signal, and failure conditions.
4. Replay on a small sample set first. Stop on ambiguity or unexpected UI.
5. Keep high-risk side effects, final submissions, purchases, messages, or permission changes behind human confirmation.
6. Turn stable flows into a skill or SOP with sample inputs, expected outputs, and recovery rules.
