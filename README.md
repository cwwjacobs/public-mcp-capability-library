# Public MCP Capability Library

Free, versioned AI capabilities for skills, tools, workflows, evals, templates, and MCP-adjacent agent systems.

This repository is the public/free tier of the capability library. It contains reusable artifacts that can be inspected, copied, tested, adapted, and verified.

## Purpose

The goal of this library is to provide practical AI capabilities that are:

- public
- reusable
- versioned
- auditable
- documented
- easy to inspect before use

## What Belongs Here

This repository may include:

- Skills
- Tools
- MCP utilities
- Workflow templates
- Eval rubrics
- Checklists
- Prompt packs
- Lightweight datasets
- Manifests
- Receipts
- Example traces

## Artifact Standard

Each artifact should include, when applicable:

```text
README.md
manifest.json
checksums.sha256
schemas/
examples/
receipts/
LICENSE or license note
```

## Suggested Repository Structure

```text
skills/
tools/
workflows/
evals/
templates/
datasets/
manifests/
receipts/
docs/
```

## Versioning

Released artifacts should be tagged or versioned.

Recommended format:

```text
artifact-name/
  manifest.json
  checksums.sha256
  README.md
```

Each manifest should identify:

- artifact name
- artifact type
- version
- files included
- checksum references
- expected inputs
- expected outputs
- expected permissions
- known limitations

## Free Tier Boundary

Everything in this repository is intended for public/free access.

Paid, managed, private, subscription-backed, or support-backed artifacts should live in a separate private release channel.

## Status

Early public capability library.

Some artifacts may be experimental, incomplete, or under active development.

## Philosophy

Capabilities should be useful before they are trusted.

Inspect first. Verify identity. Check behavior. Promote only after evidence.
