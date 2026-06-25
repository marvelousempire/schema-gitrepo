# Product Requirements Document - Schema Gitrepo

## Product Name

Schema Gitrepo

## Purpose

Schema Gitrepo is a reusable schema for designing, documenting, and maintaining Git repositories.

## Problem

Git repos often become hard to understand because they lack a consistent structure.

Important context may be spread across README files, issues, commits, chats, notes, and folders without a clear system.

## Solution

Create a reusable Git repo schema that tells an AI, founder, or developer how to build a complete repo foundation.

## Target Users

- Founders
- Builders
- Developers
- AI operators
- Documentation teams
- Product teams
- Teams using repos as knowledge systems

## Core Requirements

1. Define required root files.
2. Define required repo folders.
3. Define how docs should be organized.
4. Define how feature tickets should be tracked.
5. Define how decisions should be journaled.
6. Define how releases should be remembered.
7. Define how repo manifests should work.
8. Define how validation should work.
9. Define how another AI can use the schema.
10. Define how this schema relates to Schema Agent.

## Required Root Files

```text
README.md
ABOUT.md
PRD.md
LICENSE
repo-manifest.md
release-ledger.md
```

## Required Folders

```text
docs/
features/
features/tickets/
obsidian/
obsidian/journal/
templates/
tests/
```

## Success Criteria

Schema Gitrepo is successful when a new AI can read this repo and create a new Git repo with a clear front door, documented purpose, feature ledger, release memory, journal layer, and validation path.

## Sibling Schema

```text
schema-agent
```
