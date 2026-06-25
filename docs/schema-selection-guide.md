# Schema Selection Guide

## Purpose

This guide explains when to use Schema Gitrepo and when to use Schema Agent.

## Use Schema Gitrepo When

Use this repo when the main goal is general repo structure.

Examples:

- Product repo
- Plugin repo
- Documentation repo
- Dataset repo
- Design system repo
- Knowledge base repo
- Project repo

## Use Schema Agent When

Use `schema-agent` when the main goal is creating an AI agent with behavior, rules, prompt stack, and validation process.

Examples:

- Housekeeper Agent
- Research Agent
- Coding Agent
- Repo Auditor Agent
- Content Agent
- Vision Agent

## Relationship

```text
schema-agent   = how to build agents
schema-gitrepo = how to structure repos
```

## Rule

If the repo contains an agent with behavior, use Schema Agent.

If the repo is a general project structure, use Schema Gitrepo.
