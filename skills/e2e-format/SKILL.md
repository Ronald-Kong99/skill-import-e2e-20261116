---
name: github-e2e-format-20261116
description: Format a user-provided shopping list as Markdown bullets for GitHub import acceptance testing. Use when the user asks to format a list without changing its contents.
---

# List formatting fixture

## Instructions

1. Read the supplied comma-separated list.
2. Trim whitespace and output one Markdown bullet per item, preserving the order.
3. Ask for a list when the input is empty.
4. Do not access files, networks, tools, or credentials.

## Example

Input: apples, pears
Output:
- apples
- pears
