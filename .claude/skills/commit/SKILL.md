---
name: commit
description: Write a terse Conventional-Commits message and commit it. Use when the user says "commit", "commit this", "/commit", or asks to commit changes.
---

Compose a terse Conventional-Commits message, then commit. Why over what — the diff says what.

## Message

- Subject: `<type>(<scope>): <imperative summary>` — types `feat fix refactor perf docs test chore build ci style revert`, imperative mood, ≤50 chars (hard cap 72), no trailing period.
- Body only when the *why* isn't obvious: wrap 72, bullets `-`, issue refs last (`Closes #42`).
- Never: "this commit / I / we / now", file names already in the scope, emoji, or any `Co-Authored-By: Claude` / AI-attribution trailer (a repo hook rejects it).

## Commit

Stage the files belonging to *this* change (leave unrelated edits alone), then `git commit`. Done when `git log -1` shows the commit carrying the intended files and the working tree holds only the changes you meant to leave out.

- Committing only — no `git push`, no `--amend`, no new branch unless the user asked.
- On the default branch, commit in place unless told otherwise.
