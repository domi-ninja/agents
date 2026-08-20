---
name: unslop-help
description: Show a compact reference for the installed unslop-lite skills and invocation syntax. Use only when explicitly invoked.
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

The companion skills are explicit-only. This help skill is one-shot and must not persist state or modify files.

