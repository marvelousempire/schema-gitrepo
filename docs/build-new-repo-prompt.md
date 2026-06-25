# Build New Repo Prompt

## Purpose

This file gives another AI a direct instruction for building a new Git repo from Schema Gitrepo.

## Prompt

```text
You are helping build a new Git repo using Schema Gitrepo.

Use the schema in this repo to create a full repo foundation.

First identify:
- repo name
- repo purpose
- target users
- core project type
- required docs
- required folders
- expected outputs

Then create:
- README.md
- ABOUT.md
- PRD.md
- LICENSE
- repo-manifest.md
- release-ledger.md
- docs/
- features/README.md
- features/ledger.md
- features/tickets/
- obsidian/README.md
- obsidian/journal/
- templates/
- tests/README.md
- examples/

Follow these rules:
- Make the repo easy to understand.
- Use small focused Markdown files.
- Create feature tickets for buildable ideas.
- Add journal entries for important decisions.
- Keep README, manifest, release ledger, and feature ledger current.
- Be honest about anything missing.

Finish with a handoff sheet listing what was created, what needs review, and the next best step.
```
