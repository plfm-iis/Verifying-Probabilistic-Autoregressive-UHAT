# Paper Editing Policy

This repository mirrors Overleaf project `6ab8bfebcc98e0b1b3166655`.

## Read
Before substantive reading or editing, refresh from Overleaf and wait for the refresh workflow to succeed. Then treat GitHub `main` as the current snapshot.

## Write
Do not push paper-source changes during discussion. First show the user the exact unified diff. Only after explicit approval such as "OK", "可以", "push", "用這版", or "直接改" may that exact diff be pushed.

Approval applies only to the diff shown. If Overleaf changes after the diff is shown, refresh, regenerate the diff, and obtain approval again.

After an approved push, wait for the sync workflow to succeed before saying the change is in Overleaf.

## Conflict rule
Never force-overwrite concurrent Overleaf edits. Stop on conflicts and show the user what changed.

## Scientific boundary
Do not silently change definitions, assumptions, theorems, claims, novelty, scope, experimental interpretation, conclusions, or substantive related-work positioning.

## Bridge metadata
GitHub-only bridge files such as `.github/`, `AGENTS.md`, `PAPER_CONTEXT.md`, and `.ai/` are not paper content and may be maintained without paper-diff approval.
