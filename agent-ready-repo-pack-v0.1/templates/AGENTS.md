# AGENTS.md

Repository instructions for AI coding agents.

## Project Summary

Briefly describe:

- what this repository does
- primary language/framework
- main entry points
- test command
- build command
- important constraints

## Agent Operating Rules

1. Read this file before making changes.
2. Prefer small, bounded diffs.
3. Do not change public APIs unless the task asks for it.
4. Do not delete tests to make a run pass.
5. Do not add dependencies without explaining why.
6. Preserve existing style and structure when possible.
7. Run relevant tests before finalizing.
8. Summarize changed files and verification performed.

## Repository Map

Link or paste the repo map here:

```text
src/
tests/
docs/
scripts/
```

## Common Commands

```bash
# install
<install command>

# test
<test command>

# lint
<lint command>

# build
<build command>
```

## Safe Change Boundaries

Allowed by default:

- documentation edits
- small bug fixes
- small tests
- refactors inside the requested scope

Needs review:

- dependency changes
- broad rewrites
- generated files
- security-sensitive code
- credential/config changes
- CI/CD changes
- release/version changes

## Completion Checklist

Before final response, include:

- files changed
- tests run
- known limitations
- follow-up recommendations
