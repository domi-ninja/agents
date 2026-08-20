---
name: unslop-reasoning
description: Invoke when the user asks to clean up a visible reasoning trace, design note, or decision log they supplied.
---

# Unslop Reasoning

Rewrite only reasoning text the user supplied or explicitly asked to make presentable. Never expose or reconstruct private model reasoning.

- Remove restatements of the request, ceremonial planning, stacked hedges, exhaustive but unranked possibility lists, and repeated pros-and-cons loops.
- Collapse trivial decompositions into the actual observation and next action.
- When options repeat, name the deciding tradeoff and commit to the supported choice.
- Preserve genuine corrections when new evidence caused the change of direction.
- Keep concrete evidence exact: filenames, line numbers, commands, errors, numbers, and findings.
- Do not over-compress substantial reasoning into unsupported conclusions.
- Return the cleaned trace, not a critique of its writing, unless the user asks for analysis.

This skill applies to visible reasoning artifacts, design notes, and decision logs. It does not change ordinary final-answer style; use `$unslop-lite` for that.
