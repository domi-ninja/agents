---
name: unslop-file
description: Invoke when the user asks to rewrite prose in a text or Markdown file.
---

# Unslop File

Edit the requested prose file in place using the `unslop-lite` writing rules.

## Preserve exactly

- Fenced and indented code blocks, inline code, commands, file paths, URLs, link destinations, error messages, technical identifiers, dates, versions, and numbers.
- Markdown headings and their text, YAML frontmatter, list nesting, table structure, and blockquote structure.

## Process

1. Read the entire file and identify prose separately from protected content.
2. Rewrite only the prose. Remove filler, tighten repetition, and vary rhythm without changing meaning.
3. Apply the edit with a reviewable patch.
4. Inspect the diff and verify that protected content and factual claims did not change.

Operate only on natural-language files such as `.md`, `.txt`, `.markdown`, `.rst`, or extensionless prose. Refuse secrets, credentials, key files, and files that are primarily source code or structured data. If prose and code are mixed, edit only the prose regions.

Do not create backup files when Git already makes the change recoverable. Do not rewrite multiple files unless the invocation identifies them.
