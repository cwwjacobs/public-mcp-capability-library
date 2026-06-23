# Coding Agent Readiness Rubric

Score each category from 0 to 2.

| Category | 0 | 1 | 2 |
|---|---|---|---|
| Repo map | none | partial | clear map with paths and commands |
| Agent instructions | none | generic | repo-specific |
| Test command | unknown | listed but unverified | listed and verified |
| Build/lint command | unknown | partial | clear |
| Safe boundaries | absent | partial | explicit |
| Review gate | absent | informal | checklist-based |
| Dependency policy | absent | partial | explicit |
| Sensitive files policy | absent | partial | explicit |
| Example task | absent | partial | included |
| Receipt habit | absent | partial | required |

## Score Bands

```text
0-6: not agent-ready
7-13: partially agent-ready
14-20: agent-ready v0.1
```

## Minimum Passing Standard

A repo is agent-ready v0.1 if it has:

- agent instructions
- repo map
- test command
- safe change boundaries
- review gate
