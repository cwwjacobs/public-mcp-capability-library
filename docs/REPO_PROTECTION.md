# Repository Protection Setup

Goal: protect `main` while still allowing trusted maintainer or GitHub App writes.

## Recommended GitHub Ruleset

Create a repository ruleset targeting the default branch.

Suggested settings:

```text
Ruleset name: protect-main
Target: branch
Branch pattern: main
Enforcement: Active
Block force pushes: On
Block deletions: On
Require pull request: Optional for now
Require status checks: Off for now
Require signed commits: Off for now
Bypass list: repository admin and/or trusted GitHub App connector
```

## Why

This keeps the public library from accidental or drive-by mutation while still allowing authorized maintenance writes.

## Notes

- `CODEOWNERS` is present, but it only becomes enforceable when GitHub rules require code owner review.
- If strict pull-request-only protection is enabled without bypass, automated connector writes to `main` may fail.
- If connector writes stop working, check whether the GitHub App or repository administrator role is included in the ruleset bypass list.

## Current Intended Policy

```text
Public repo: readable by everyone
Main branch: protected
Maintainer/App writes: allowed through bypass
External contributions: PR path
Paid/subscription assets: separate private channel
```
