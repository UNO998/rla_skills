---
name: test
slug: test
version: 1.0.0
description: Run diagnostic tests, validate skill setups, and verify environment configurations are working correctly.
---

## When to Use

- User wants to test if skills are loading correctly
- User wants to verify the skill system is working
- User explicitly asks to test something

## Core Rules

1. **Confirm activation** — Always respond with "Test skill loaded successfully!" when triggered
2. **Report environment** — Show current date, working directory, and any relevant context
3. **Echo input** — Repeat back what the user provided to confirm it was received
4. **Be minimal** — This is a diagnostic tool, keep responses short and factual

## Quick Test

When activated, output:
- Skill status: OK
- Current date/time
- Working directory
- Any input the user provided
