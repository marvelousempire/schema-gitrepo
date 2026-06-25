# Schema Gitrepo

**Structure the repo. Preserve the memory. Make the work reusable.**

Schema Gitrepo is the reusable schema for creating Git repos the way this system structures them: README-first, manifest-aware, feature-ticket driven, journaled, wiki-ready, release-aware, validation-friendly, and AI-ready.

This repo is not one product.

It is the pattern for making repos.

## Purpose

Schema Gitrepo defines how to create a safe, useful, well-structured Git repo from the ground up.

It captures the root files, folders, docs, feature ledger, tickets, Obsidian notes, journals, release memory, validation notes, and templates that make a repo easy for humans and future AI systems to understand.

## Core Idea

A repo should not be a pile of files.

A repo should have:

```text
Purpose
Front Door
Manifest
Release Memory
Feature Ledger
Tickets
Docs
Wiki Notes
Journal
Templates
Tests
Validation
```

## What This Schema Creates

A new repo built from this schema should include:

```text
README.md
ABOUT.md
PRD.md
LICENSE
repo-manifest.md
release-ledger.md
docs/
features/
features/tickets/
obsidian/
obsidian/journal/
templates/
tests/
```

## Gitrepo-Building Rule

Every important repo area should have a place.

Nothing important should be invisible.

When a repo changes in a meaningful way, update the README, manifest, release ledger, feature ledger, and journal when needed.

## Start Here

- [About](ABOUT.md)
- [PRD](PRD.md)
- [Repo Manifest](repo-manifest.md)
- [Release Ledger](release-ledger.md)
- [Git Repo Schema](docs/git-repo-schema.md)
- [Repo Build Process](docs/repo-build-process.md)
- [Repo Folder Standard](docs/repo-folder-standard.md)
- [Feature Ticket Pattern](docs/feature-ticket-pattern.md)
- [Journal Pattern](docs/journal-pattern.md)
- [Release Ledger Pattern](docs/release-ledger-pattern.md)
- [Validation Pattern](docs/validation-pattern.md)

## Build A New Repo

- [New Repo Checklist](docs/new-repo-checklist.md)
- [Build New Repo Prompt](docs/build-new-repo-prompt.md)
- [Minimum Viable Git Repo](docs/git-repo-minimum-viable-repo.md)
- [Schema Selection Guide](docs/schema-selection-guide.md)

## Related Schema

This repo covers general Git repo structure.

The sibling schema for agent creation is:

```text
schema-agent
```

## Status

Version: `v0.1.0-origin`
