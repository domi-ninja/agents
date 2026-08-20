---
name: unslop-commit
description: Write or clean up a concise, specific Conventional Commit message without AI or marketing filler. Use only when explicitly invoked.
---

# Unslop Commit

Produce a paste-ready commit message from the supplied context or repository diff.

- Use `<type>(<scope>): <imperative summary>`. The scope is optional.
- Choose an accurate type such as `feat`, `fix`, `refactor`, `docs`, `test`, `perf`, `build`, `ci`, `chore`, or `revert`.
- Aim for 50 characters in the subject; never exceed 72. Use imperative mood and no trailing period.
- Add a body only when the reason, migration impact, security context, or breaking behavior is not obvious from the subject. Wrap it at 72 characters.
- Prefer the reason for the change over a list of touched files.
- Remove template phrases such as "This commit" and "This change", marketing language, filler adverbs, emojis, and AI attribution unless repository conventions require them.
- Never invent motivation, issue numbers, or breaking-change details. Inspect the relevant diff when available.
- Return only the commit message in one fenced block.
- Do not stage, commit, amend, or push unless the user separately asks for that action.

