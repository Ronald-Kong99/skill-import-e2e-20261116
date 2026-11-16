---
name: github-e2e-mirror-20261116
description: Format a short greeting for GitHub mirror import acceptance testing. Use when the user requests the mirror test greeting.
---

# Mirror import acceptance fixture

## Workflow
1. Read the name supplied by the user.
2. If the name is missing, ask for it.
3. Return exactly `Welcome, <name>!` as plain text.

## Example
Input: Alice
Output: Welcome, Alice!

## Constraints
Do not call external services or modify files. This fixture contains no executable code.
