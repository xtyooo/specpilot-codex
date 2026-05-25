---
description: Confirm a DefSpec draft by clarifying scope, rules, boundaries, and tests.
argument-hint: REQ-xxx
---

# DefSpec Confirm

The user invoked this command with: $ARGUMENTS

Use this command to turn a draft requirement into a confirmed requirement.

## Preflight

1. Read the required DefSpec context files.
2. Read the target `REQ-xxx` draft and requirement index.
3. Inspect relevant code paths enough to understand feasibility and integration boundaries.

## Plan

1. Identify unclear scope, business rules, edge cases, and test obligations.
2. Ask concise clarification questions only when needed.
3. Update the requirement with confirmed details after the user answers.
4. Do not implement code in this command.

## Commands

1. Normalize terminology and requirement boundaries.
2. Record acceptance criteria and non-goals.
3. Record impacted modules, data flows, compatibility constraints, and test cases.
4. Mark the requirement status as `confirmed` when enough detail is available.

## Verification

1. Re-read the confirmed requirement.
2. Confirm ambiguity has been reduced enough for design.
3. Confirm the index reflects the new status.

## Summary

Report what was confirmed, what remains risky, and the target requirement file.

## Next Steps

Suggest `/defspec:exec REQ-xxx` to design and implement after confirmation.
