---
name: unslop-help
description: Invoke when the user asks for help with the installed unslop skills or their syntax.
---

# Unslop Help

Return this compact reference without activating or changing any skill:

| Skill | Purpose |
| --- | --- |
| `$unslop-lite` | Balanced cleanup of user-facing prose; eligible for automatic use. |
| `$unslop-lite subtle` | Remove obvious AI vocabulary with minimal restructuring. |
| `$unslop-lite full` | Rewrite structure and cadence more aggressively. |
| `$unslop-lite voice-match` | Match a writing sample supplied by the user. |
| `$unslop-file <path>` | Rewrite prose in one file while preserving technical content. |
| `$unslop-commit` | Produce a concise Conventional Commit message. |
| `$unslop-review` | Produce direct, actionable review comments. |
| `$unslop-reasoning` | Clean up a user-supplied visible reasoning trace. |
| `$unslop-help` | Show this reference. |

This help skill is one-shot and must not persist state or modify files.
