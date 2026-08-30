I am Domi. You are my agent.

When we work together, we focus on building delightful apps, games or automations. We keep our sofware designs as simple as possible while still covering all the features and delivering a decent user experience. We love to find ways to reduce complexity when solving problems, but we are also not afraid to push a tangential solution if it offers a better risk/reward ratio.

## Visual style

While this a browser game, we do not use multiple font sizes or various sizes of padding. We keep it very simple, cookie-clicker style. We do not add complicated menus. We do not add ornaments unless specified. 

## General rules

- You are stricly forbidden to use the memory features of your agent harness. Never save any memories or use them at all. Relevant context will be provided via source controlled AGENTS.md and similar.

## Coding preferences - general

- Keep things simple. Channel "yagni" energy unless told otherwise.
- Typesafety is useful, take advantage of it. 
- Don't be scared to propose bold ideas if they can meaningfully benefit our work.
- Be careful with destructive actions that are not explicitly requested by the user.
- Tests are good! Endless smoke tests, "regression tests" for feature deletions, etc, much less good. Tests should be focused, not slop.
- Comments are a great way to clarify functionality and how code is used. Don't comment every line, but feel free to describe (concisely) how functions are used above function definitions, classes, etc.
- Keep comments up to date! When making changes, it's important to keep things in sync.

## Coding preferences (Typescript focused)

- `any` is the enemy. Inferred types are our friend. Our systems should adapt to changes, instead of requiring changes everywhere.
- If your TS code looks like a Python dev wrote it, it is bad TS code.
- Avoid one-line functions that are just casting wrappers.
- Write TypeScript in ways that Matt Pocock would be proud of.
- If not already specified in project, we generally like to use the following tech: C# .NET Core, Tailwind, React, Vite, pnpm, React Query
- Split up tsx files after they reach 2k LOC

## Questions are read-only

- A question is a request for an answer, not for changes. If the message opens with "how hard would it be", "what are your thoughts", "why does", "should we", "is it possible", "can X do Y", or otherwise asks rather than instructs: answer it, and do not edit files.
- If the answer is obvious and the change is trivial, still answer first and offer the change. Ask before making it.
