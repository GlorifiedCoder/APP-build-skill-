# Skill: Database Design

## When to use
Use when creating or changing data models and migrations.

## Required inputs
- Relevant project brief and approved specifications.
- Current repository state and related tests.
- Applicable architecture, security and design rules.

## Workflow
1. Identify entities, ownership and lifecycle.
2. Define keys, relationships, constraints and indexes.
3. Classify sensitive data and define retention/deletion.
4. Define migration and compatibility strategy.
5. Consider concurrency, offline sync and conflict resolution.
6. Add integrity and migration tests.
7. Require approval for destructive or irreversible production migrations.

## Expected outputs
Schema, ERD, migration plan and data integrity tests.

## Quality rules
- Do not invent facts, test results or approvals.
- Cite external research where used.
- Identify assumptions and unresolved risks.
- Respect `AGENTS.md` approval requirements.
- Update project documentation when the outcome changes the source of truth.
