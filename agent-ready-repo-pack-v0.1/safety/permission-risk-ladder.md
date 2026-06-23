# Permission Risk Ladder

Use this to classify what an agent is allowed to do in a repository.

## Level 0: Read-only

Examples:

- inspect files
- search repository
- read documentation
- run harmless status commands

Default: allowed.

## Level 1: Local edits

Examples:

- edit source files
- edit tests
- edit documentation

Default: allowed when task requires it.

## Level 2: Local execution

Examples:

- run tests
- run linters
- run local build commands

Default: allowed when commands are known and scoped.

## Level 3: Dependency or environment changes

Examples:

- install packages
- update lockfiles
- change Docker config
- change CI config

Default: review before final acceptance.

## Level 4: External or persistent actions

Examples:

- publish package
- deploy service
- push to remote
- send email
- write to external system
- use production credentials

Default: hold for operator approval.
