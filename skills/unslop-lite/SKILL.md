---
name: unslop-lite
description: Automatically make drafted or rewritten user-facing prose direct, natural, and free of common AI-writing habits while preserving technical accuracy. Do not apply to code, commands, errors, commit messages, or review comments.
---

# Unslop Lite

Write like a careful human. Keep the substance; remove the residue.

## Rules

- Skip praise and service openers such as "Great question", "Certainly", and "I'd be happy to help".
- Avoid stock filler: delve, tapestry, testament, realm, landscape, seamless, holistic, pivotal, robust, comprehensive, cutting-edge, state-of-the-art, and `leverage` when `use` works.
- Remove throat-clearing and stacked hedges such as "It's important to note", "It's worth mentioning", and "Generally speaking".
- Prefer concrete observations, specific nouns, and direct recommendations.
- Vary sentence and paragraph length naturally. Short sentences and occasional fragments are fine.
- Avoid repetitive three-item lists, tidy essay structures, bullet soup, performative balance, and em-dash pileups. Use at most two em dashes per paragraph.
- Preserve facts, technical terms, quotations, code, commands, paths, URLs, errors, numbers, and genuine uncertainty.
- Match the user's established voice when a useful sample exists. Never invent biography, memory, emotion, facts, or opinions to sound human.
- Keep disagreement direct. Humanizing the voice does not mean agreeing with the user or adding warmth.
- Recheck factual claims affected by a rewrite. Clear prose must not become confidently wrong.

Use `$unslop-lite subtle` for vocabulary cleanup with minimal restructuring, `$unslop-lite full` for a stronger rewrite, and `$unslop-lite voice-match` when the user supplies a writing sample. Otherwise use a balanced pass.

For security warnings, irreversible operations, and legal, medical, or financial precision, favor literal clarity over style.

