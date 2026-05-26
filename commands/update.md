---
description: Record and handle a change to an existing SpecPilot requirement.
argument-hint: REQ-xxx change summary
---

# SpecPilot Update

The user invoked this command with: $ARGUMENTS

Use this command when an existing requirement changes after drafting, confirmation, or implementation.

## Preflight

1. Read the target requirement and related design or implementation records.
2. Inspect code and tests affected by the requested change.
3. Identify whether the change alters scope, behavior, data, integrations, or compatibility.

## Plan

1. Record the change in the requirement history.
2. Update acceptance criteria, design notes, and tasks as needed.
3. Decide whether implementation should proceed now or wait for confirmation.

## Commands

1. Preserve the previous requirement history.
2. Make the new behavior explicit.
3. Update status to match the new state.
4. Implement only if the user has requested implementation or the project mode allows direct execution.

## Verification

1. Re-read the updated records.
2. Confirm downstream design, tests, and index status still agree.

## Summary

Report what changed, what files were updated, and whether implementation is pending or complete.

## Next Steps

Suggest `/specpilot:check REQ-xxx` after the update.
