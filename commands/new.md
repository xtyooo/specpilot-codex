---
description: Create the next SpecPilot requirement draft and update the requirement index.
argument-hint: [requirement summary]
---

# SpecPilot New

The user invoked this command with: $ARGUMENTS

Use this command to start a new requirement before implementation.

## Preflight

1. Read `docs/specpilot/SPECPILOT.md`, `docs/specpilot/project.md`, and `docs/specpilot/project-guide.md` if they exist.
2. Read `docs/specpilot/requirements/index.md` if it exists.
3. Inspect the current repo enough to understand the requested capability.
4. If SpecPilot docs are missing, explain that the project should run `npx github:xtyooo/specpilot-codex` first.

## Plan

1. Choose the next `REQ-xxx` id from the index or existing requirement files.
2. Create a draft requirement record under `docs/specpilot/requirements/`.
3. Update `docs/specpilot/requirements/index.md`.
4. Do not implement code in this command.

## Commands

1. Capture the user request, scope, motivation, assumptions, and open questions.
2. Record success criteria, likely impacted areas, and test ideas.
3. Mark the requirement status as `draft`.
4. Keep the draft concise and easy to confirm in the next step.

## Verification

1. Re-read the created draft and index entry.
2. Confirm the requirement id is unique.
3. Confirm no code files were changed unless the user explicitly requested otherwise.

## Summary

Report the created requirement id, file path, status, and recommended next command.

## Next Steps

Suggest `/specpilot:confirm REQ-xxx` when the draft is ready to clarify.
