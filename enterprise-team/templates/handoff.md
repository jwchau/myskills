# <Step> · <Role Name> (<mode>)

**Status:** DONE | APPROVED | REJECTED | BLOCKED
**Summary:** <one sentence: what you did. The orchestrator uses it as the commit message.>

<!--
Status rules:
- DONE: you finished your job (or your role wasn't needed; say why in the summary).
- APPROVED / REJECTED: reviewer steps only (Senior Engineer review, QA, EM sign-off).
- BLOCKED: you truly could not do your job (for example, there is no code to test).
  Missing information is NOT a block: make an assumption and carry on.
Delete this comment and any sections below that would be empty, except Status and Summary.
-->

## What I did
<Short bullet list of the work, in the order you did it.>

## Decisions
<Choices you made and why, so later roles don't relitigate them.>

## Assumptions
<Anything you had to guess because the brief or earlier handoffs didn't say. One line each.>

## Files changed
<Path, then a few words on what changed. Include docs you wrote.>

## For the next roles
<What later roles need to know or do, addressed by role where it matters, e.g. "QA: test the empty-input case".>

## Review verdict
<Reviewer steps only.>
- **send_back_to:** <role id that must fix this, when REJECTED>
- **Issues:** <numbered list, each specific enough to fix without asking: what, where, why it matters>
- **Checked and fine:** <what you verified that passed>

## Rework response
<Rework mode only: for each numbered issue from the reviewer, what you changed, or why you disagree.>

## Requested outward actions
<Anything you would do but are not allowed to: push, PR, deploy, publish, send, system-wide install.
For each: the exact command or action, why, and whether later roles are blocked without it.>

## Blocker
<BLOCKED only: what stopped you and what would unblock it.>
