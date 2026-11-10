# Skill: Code Review

## When to use
Use after implementation or before merging changes.

## Required inputs
- Relevant project brief and approved specifications.
- Current repository state and related tests.
- Applicable architecture, security and design rules.

## Workflow
1. Review diff and related requirements.
2. Check correctness, edge cases and maintainability.
3. Check architecture boundaries and duplication.
4. Check security, privacy and performance implications.
5. Check test quality and missing scenarios.
6. Report findings with severity, file/line and remediation.
7. Re-review fixes.

## Expected outputs
Prioritized review findings and merge recommendation.

## Quality rules
- Do not invent facts, test results or approvals.
- Cite external research where used.
- Identify assumptions and unresolved risks.
- Respect `AGENTS.md` approval requirements.
- Update project documentation when the outcome changes the source of truth.
