---
id: 1
title: Establish Project Constitution
stage: constitution
date: 2025-11-21
surface: agent
model: gemini
feature: none
branch: main
user: user
command: /sp.constitution
labels: [constitution, principles, standards]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
- .specify/memory/constitution.md
- .specify/templates/plan-template.md
- .specify/templates/tasks-template.md
tests:
- 
---

## Prompt

/sp.constitution 

Project principles and standards:
- Write tests first (TDD approach)
- Use Python 3.12+ with type hints everywhere
- Keep code clean and easy to read
- Document important decisions with ADRs
- Follow essential OOP principles: SOLID, DRY, KISS

Technical stack:
- Python 3.12+ with UV package manager
- pytest for testing
- Keep all project files in git

Quality requirements:
- All tests must pass
- At least 80% code coverage
- Use dataclasses for data structures

## Response snapshot

I have updated the project constitution and propagated the changes to the relevant templates.

- New version: 1.0.0
- The constitution has been updated at `.specify/memory/constitution.md`.
- The following templates have been updated to align with the new constitution:
  - `.specify/templates/plan-template.md`
  - `.specify/templates/tasks-template.md`

I suggest you commit these changes: `docs: amend constitution to v1.0.0 (principle additions + governance update)`

## Outcome

- ✅ Impact: Established the project constitution and updated related templates.
- 🧪 Tests: None
- 📁 Files: 
  - `.specify/memory/constitution.md`
  - `.specify/templates/plan-template.md`
  - `.specify/templates/tasks-template.md`
- 🔁 Next prompts: None
- 🧠 Reflection: The user has established the core principles and standards for the project. This will guide all future development.

## Evaluation notes (flywheel)

- Failure modes observed: None
- Graders run and results (PASS/FAIL): None
- Prompt variant (if applicable): None
- Next experiment (smallest change to try): None
