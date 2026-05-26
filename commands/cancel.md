---
description: Cancel a SpecPilot requirement without deleting its history.
argument-hint: REQ-xxx
---

# SpecPilot Cancel

The user invoked this command with: $ARGUMENTS

Use this command when a requirement should no longer be implemented.

## Preflight

1. Read the target requirement and index.
2. Check whether any implementation work already exists.
3. Identify whether cleanup is needed.

## Plan

1. Record why the requirement is cancelled.
2. Preserve the requirement history.
3. Update the index and status.
4. Do not delete records.

## Commands

1. Mark the requirement as `cancelled`.
2. Add cancellation notes and any replacement requirement link.
3. If code cleanup is needed, ask before changing implementation files.

## Verification

1. Re-read the requirement and index.
2. Confirm the record remains discoverable.

## Summary

Report the cancelled requirement id and any cleanup or replacement next steps.

## Next Steps

Suggest `/specpilot:new` if the cancelled work should be replaced by a new requirement.
