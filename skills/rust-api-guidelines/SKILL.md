---
description: Use when the agent must read, apply, or review against the official Rust API Guidelines from rust-lang.github.io and must fetch the live pages first instead of relying on memory or local copies. Trigger this skill for Rust API design reviews, crate audits, naming checks, documentation checks, macro guidance, predictability and flexibility reviews, type-safety and dependability reviews, debuggability and future-proofing checks, or any request to consult the Rust API Guidelines online.
---

# Rust API Guidelines

## Overview

Read the official Rust API Guidelines live from the web before doing any other work.
Use only the pages opened in the current turn as the source of truth for the task.

## Required First Step

Before any analysis, summary, code review, recommendation, or other action:

1. Open each URL below with the web fetch tool, one by one, in the exact order shown.
2. Treat any failure to open a page as a hard stop.
3. If any page cannot be opened, stop immediately, report the failing URL, and do not continue.
4. Do not use memory, local files, cached copies, or paraphrases remembered from earlier turns as a substitute.
5. Read the rendered pages directly.

Open this sequence exactly:

1. `https://rust-lang.github.io/api-guidelines/`
2. `https://rust-lang.github.io/api-guidelines/checklist.html`
3. `https://rust-lang.github.io/api-guidelines/naming.html`
4. `https://rust-lang.github.io/api-guidelines/interoperability.html`
5. `https://rust-lang.github.io/api-guidelines/macros.html`
6. `https://rust-lang.github.io/api-guidelines/documentation.html`
7. `https://rust-lang.github.io/api-guidelines/predictability.html`
8. `https://rust-lang.github.io/api-guidelines/flexibility.html`
9. `https://rust-lang.github.io/api-guidelines/type-safety.html`
10. `https://rust-lang.github.io/api-guidelines/dependability.html`
11. `https://rust-lang.github.io/api-guidelines/debuggability.html`
12. `https://rust-lang.github.io/api-guidelines/future-proofing.html`
13. `https://rust-lang.github.io/api-guidelines/necessities.html`

## Operating Rules

- Do not search for alternate mirrors or summaries before finishing the required open sequence.
- Do not inspect local copies of the guidelines.
- Do not answer from prior knowledge.
- After all pages open successfully, use the live pages from this turn as the authoritative source.
- If the user asks for citations or quotes, cite the relevant Rust API Guidelines page URL.

## Failure Handling

If any required page fails to open:

1. Stop immediately.
2. State that the Rust API Guidelines could not be fully loaded live.
3. Identify the exact URL that failed.
4. Do not continue the task until the missing page can be opened.
