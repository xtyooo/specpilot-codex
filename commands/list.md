---
description: List SpecPilot requirements and summarize their current statuses.
---

# SpecPilot List

The user invoked this command with: $ARGUMENTS

Use this command to show requirement status without changing files.

## Preflight

1. Check whether `docs/specpilot/requirements/index.md` exists.
2. If it is missing, look for requirement files under `docs/specpilot/requirements/`.

## Plan

1. Read the requirement index.
2. Summarize active requirements first.
3. Include archived or cancelled items after active work.

## Commands

1. Group requirements by status.
2. Show requirement id, title, status, and short next action.
3. Read individual requirement files only when the index is incomplete or the user asks for details.

## Verification

1. Confirm listed ids match existing files when possible.
2. Mention missing or inconsistent records.

## Summary

Provide a compact status overview.

## Next Steps

Suggest the most relevant follow-up command, such as `/specpilot:check REQ-xxx` or `/specpilot:confirm REQ-xxx`.
