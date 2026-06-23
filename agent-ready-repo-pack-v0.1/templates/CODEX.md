# CODEX.md

Codex-oriented repository guidance.

## Mission

Complete bounded coding tasks with small, reviewable changes and clear verification.

## Working Pattern

1. Inspect relevant files.
2. Plan the smallest viable change.
3. Edit only files required for the task.
4. Run targeted tests.
5. Report changed files, verification, and remaining risks.

## Command Policy

Allowed:

```bash
ls
find
grep
rg
cat
sed
python -m pytest
npm test
git diff
```

Review before use:

```bash
network fetch commands
permission-changing commands
container commands
admin commands
remote push commands
deployment commands
package publish commands
```

## Final Response Format

```text
Done:
-

Changed:
-

Verified:
-

Not done / needs review:
-
```
