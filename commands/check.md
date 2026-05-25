---
description: Review a DefSpec requirement against design, implementation, tests, and risks.
argument-hint: REQ-xxx
---

# DefSpec Check

The user invoked this command with: $ARGUMENTS

Use this high-frequency command to audit whether a requirement and implementation are aligned.

## Preflight

1. Read the required DefSpec context files.
2. Read the target requirement, design, task, and index records.
3. Inspect relevant code, tests, and current git status.

## Plan

1. Compare requirement intent, accepted scope, implementation state, tests, and documentation.
2. Prioritize concrete findings over general summaries.
3. Do not change files unless the user explicitly asks for fixes.

## Commands

1. Check for missing scope, extra scope, behavior regressions, weak edge-case handling, and stale records.
2. Check whether tests match the requirement risk.
3. Check whether `requirements/index.md`, requirement status, design notes, and implementation notes agree.
4. Surface blockers, likely bugs, and missing validation first.

## Verification

1. Cite local files and lines where useful.
2. If no findings are found, say that explicitly and list residual risks or unrun tests.
3. Avoid claiming success without evidence.

## Summary

Report findings first, then a short status assessment.

## Next Steps

Suggest `/defspec:update REQ-xxx` for requirement changes, `/defspec:exec REQ-xxx` for fixes, or `/defspec:archive REQ-xxx` when complete.
