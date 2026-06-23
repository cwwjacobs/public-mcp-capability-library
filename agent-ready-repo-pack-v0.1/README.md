# Agent-Ready Repo Pack v0.1

A free public capability pack for preparing repositories for AI coding agents.

This pack helps repo owners give Claude Code, Codex, Copilot, Cursor, and other coding agents a clear operating map, safe boundaries, review gates, and repeatable acceptance criteria.

## Purpose

Agentic coding works better when a repository has explicit guidance.

This pack provides:

- repo-level agent instructions
- model-specific instruction templates
- repository mapping template
- review gate template
- coding-agent readiness rubric
- before/after run receipt template
- permission risk ladder
- tool-use checklist
- tiny example repo structure

## Intended Use

Copy the templates into a project repository, adapt them to the project, then run a coding agent against a small bounded task.

The expected outcome is not magic autonomy. The expected outcome is a repository that is easier for agents to inspect, modify, test, and review.

## Included Files

```text
templates/AGENTS.md
templates/CLAUDE.md
templates/CODEX.md
templates/repo-map.md
templates/review-gate.md
evals/coding-agent-readiness-rubric.md
evals/before-after-run-receipt.md
safety/permission-risk-ladder.md
safety/tool-use-checklist.md
examples/tiny-python-repo-example/README.md
receipts/sample-agent-run.jsonl
manifest.json
checksums.sha256
```

## Artifact Standard

This pack follows the public capability library standard:

- documented
- versioned
- manifest-backed
- checksum-backed
- inspectable before use

## Recommended First Test

Use the pack on a tiny repo task:

```text
Task: update one function and one test.
Success: tests pass, diff is small, agent explains changed files, and review gate is complete.
```

## Free Tier Boundary

This artifact is part of the public/free capability library.

Paid or managed versions may add custom repo audits, private templates, trace analysis, or team-specific adoption support.
