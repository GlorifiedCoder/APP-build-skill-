# AI Engineering Starter Kit — Universal Mobile Edition

A reusable, approval-gated engineering framework for taking mobile application ideas from discovery to production.

## What this kit provides

- A root `AGENTS.md` contract for a single AI coding agent.
- Reusable engineering skills under `.agents/skills/`.
- Project documentation templates under `docs/`.
- Product, architecture, design, security, QA and production workflows.
- Approval gates for architecture, sensitive operations and production release.
- Checklists, decision records and task tracking templates.

## Quick start

1. Copy this repository into a new project, or use it as a template repository.
2. Read `AGENTS.md`.
3. Fill `project/PROJECT_BRIEF.md`.
4. Ask the agent to run `workflows/01-discovery-and-planning.md`.
5. Review and approve the PRD, design direction, architecture and implementation plan.
6. Implement in small vertical slices.
7. Require test evidence before marking work complete.
8. Deploy to staging, complete release checks and approve production release.

## Directory guide

- `AGENTS.md`: mandatory agent behavior and safety contract.
- `.agents/skills/`: reusable task-specific workflows.
- `project/`: project-specific brief and decisions.
- `docs/`: project documentation and templates.
- `workflows/`: end-to-end operating procedures.
- `checklists/`: approval and release checklists.
- `tools/`: recommended tools and integration policy.
- `examples/`: sample completed artifacts.

## Important operating rule

The agent may autonomously inspect, plan, edit code, run local tests and update documentation within the approved scope. It must ask before changing the approved architecture, adding material recurring costs, using production credentials, performing destructive data operations, publishing externally, or deploying to production.

Never commit secrets. Use placeholders in `.env.example` and secret storage in the actual environment.
