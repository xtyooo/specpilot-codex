---
description: Archive a completed SpecPilot requirement with implementation and validation notes.
argument-hint: REQ-xxx
---

# SpecPilot Archive

The user invoked this command with: $ARGUMENTS

Use this command when a requirement is accepted as complete.

## Preflight

1. Read the target requirement, index, implementation notes, and test evidence.
2. Inspect current git status for unfinished work.
3. If validation is missing, report the gap before archiving.

## Plan

1. Confirm the requirement is complete.
2. Add final implementation notes and validation evidence.
3. Update the requirement status and index.

## Commands

1. Mark the requirement as completed or archived according to project convention.
2. Preserve the requirement history.
3. Record any residual risks or follow-up requirements.

## Verification

1. Re-read the requirement and index.
2. Confirm the archive status is consistent.

## Summary

Report the archived requirement id, validation evidence, and any follow-up items.

## Next Steps

Suggest starting a new requirement with `/specpilot:new` only if there is follow-up scope.
