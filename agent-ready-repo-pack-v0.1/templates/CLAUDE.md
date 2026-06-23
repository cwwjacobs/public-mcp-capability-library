# CLAUDE.md

Claude-specific repository guidance.

## Role

You are working as a coding assistant inside this repository.

## Before Editing

- Inspect the relevant files.
- Identify the smallest safe change.
- Confirm the expected test command.
- Avoid broad rewrites unless requested.

## During Editing

- Keep changes scoped.
- Preserve project style.
- Add or update tests when behavior changes.
- Prefer clear code over clever code.

## After Editing

Return:

```text
Summary:
-

Changed files:
-

Verification:
-

Risks / notes:
-
```

## Stop Conditions

Stop and ask for review if:

- the task requires secrets or credentials
- the task requires production deployment
- the task requires deleting data
- tests reveal unrelated failures
- the requested change conflicts with repo instructions
