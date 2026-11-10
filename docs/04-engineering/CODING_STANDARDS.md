# Coding Standards

## General
- Follow idiomatic language conventions.
- Prefer explicit, readable code over clever abstractions.
- Keep functions and modules cohesive.
- Validate external input.
- Avoid silent exception swallowing.
- Use structured logging without secrets.
- Document non-obvious decisions, not obvious syntax.

## Architecture
- Keep UI separate from business rules.
- Keep business rules independent of framework details where practical.
- Depend on interfaces at important boundaries.
- Avoid circular dependencies.

## Dependencies
- Justify new dependencies.
- Check maintenance, license, security and platform support.
- Lock versions reproducibly.

## Review
- Format and lint.
- Test changed behavior.
- Inspect diff for unrelated changes and secrets.
