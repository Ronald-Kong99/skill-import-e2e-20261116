---
name: github-e2e-summary-20261116
description: Summarize a short user-provided text into two bullet points for import acceptance testing. Use when the user asks for a concise summary fixture.
---

# Summary fixture

## Instructions

1. Read only the text supplied in the current request.
2. Return exactly two concise bullet points covering its main ideas.
3. If the text is missing, ask the user to provide it.
4. No tools, network access, file changes, or credentials are required.

## Example

Input: The team met on Monday. They agreed to test the feature on Friday.
Output:
- The team met on Monday.
- Feature testing is planned for Friday.
