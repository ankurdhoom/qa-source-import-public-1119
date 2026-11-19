---
name: qa-source-import-public-1119
description: Formats a supplied synthetic QA label into a three-line checklist for staging source-import testing.
license: MIT
---
# Throwaway source-import QA fixture

This fixture contains no real user data and is intended for staging QA only.

## Procedure

1. Read the synthetic label supplied by the tester. Use `sample` if none is supplied.
2. Return exactly three checklist lines: `Input: <label>`, `Check: fixture loaded`, and `Result: ready`.
3. Do not access the network, read other files, run commands, or request credentials.

## Example

Input label: `sample`

```text
Input: sample
Check: fixture loaded
Result: ready
```
