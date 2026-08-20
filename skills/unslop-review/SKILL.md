---
name: unslop-review
description: Write or clean up direct, specific, and actionable code-review comments without corporate politeness filler. Use only when explicitly invoked.
---

# Unslop Review

Produce paste-ready review comments that are direct about the code and respectful toward the author.

- State the location, concrete problem, consequence, and a workable fix or genuine question.
- Preserve exact line numbers, ranges, identifiers, paths, and error messages.
- Use `bug:`, `risk:`, `nit:`, or `q:` only when the label adds useful severity or intent.
- Remove throat-clearing, stacked hedges, per-comment praise, vague objections, and restatements of the diff.
- Use calibrated uncertainty when evidence is incomplete; do not soften a real bug into a nit.
- Give security findings and architectural disagreements enough prose to explain the risk.
- If nothing actionable is wrong, return `LGTM` without boilerplate.
- Output comments only. Do not approve, merge, commit, push, or post them externally.

Preferred shape:

```text
path/to/file.ts:L42: bug: `findUser` can return undefined. Guard before reading `user.email` or return 404.
```

