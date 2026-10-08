# AGENTS.md

Shared instructions for every AI agent working in this repo (Claude and Codex).
Codex reads this file automatically. Claude reads it at the start of each session.

## Project

_TBD — describe what we're building, the stack, and how to run it._

- **Language / framework:** TBD
- **Install:** TBD
- **Run:** TBD
- **Test:** TBD

## How we collaborate

1. **Check `TASKS.md` first.** Only work on tasks assigned to you, or unassigned
   tasks you claim by putting your name on them in the same commit.
2. **One branch per task.** Name branches `claude/<short-task>` or `codex/<short-task>`.
   Never commit directly to `main`.
3. **Open a PR for every change.** The PR description says what changed, why,
   and anything the other agent needs to know.
4. **Don't rewrite each other's open PRs.** Leave review comments instead.
   The human owner merges.
5. **Update `TASKS.md`** in your PR: move the task to Done, and add any
   follow-up tasks you discovered.
6. **Keep notes in the repo, not in chat.** Decisions that matter go in
   `TASKS.md` (Decisions section) so the other agent can see them.

## Conventions

- Run the tests before opening a PR; don't open a PR with failing tests.
- Keep PRs small and focused on one task.
- Ask the human (in the PR description) when a decision is ambiguous rather than guessing.
