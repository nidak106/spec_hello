<!--
Sync Impact Report:
- Version change: 0.0.0 -> 1.0.0
- Modified principles:
  - [PRINCIPLE_1_NAME] -> I. Test-First (NON-NEGOTIABLE)
  - [PRINCIPLE_2_NAME] -> II. Modern Python with Static Typing
  - [PRINCIPLE_3_NAME] -> III. Clean and Readable Code
  - [PRINCIPLE_4_NAME] -> IV. Architectural Decision Records (ADRs)
  - [PRINCIPLE_5_NAME] -> V. Quality Gates
  - [PRINCIPLE_6_NAME] -> VI. Version Control
- Added sections:
  - Technology Stack
  - Development Workflow
- Removed sections: None
- Templates requiring updates:
  - ✅ .specify/templates/plan-template.md
  - ✅ .specify/templates/spec-template.md
  - ✅ .specify/templates/tasks-template.md
- Follow-up TODOs: None
-->
# spec_hello Constitution

## Core Principles

### I. Test-First (NON-NEGOTIABLE)
TDD mandatory: Tests are written and approved by the user before implementation. The Red-Green-Refactor cycle is strictly enforced.

### II. Modern Python with Static Typing
All code must be written in Python 3.12+ and use type hints for all function signatures and variables.

### III. Clean and Readable Code
Code should be self-documenting, with clear names and a logical structure. Follow essential OOP principles: SOLID, DRY, KISS.

### IV. Architectural Decision Records (ADRs)
Document all significant architectural decisions using ADRs. This includes choices of libraries, frameworks, and patterns.

### V. Quality Gates
All tests must pass before merging. Code coverage must be at least 80%. Use dataclasses for data structures.

### VI. Version Control
All project files must be committed to the git repository.

## Technology Stack

- Python 3.12+ with UV package manager
- pytest for testing
- Git for version control

## Development Workflow

- All work is done on feature branches.
- All code is reviewed via Pull Requests.
- All PRs must pass all quality gates before being merged.

## Governance

This constitution is the single source of truth for all development practices. Any amendments require a PR and approval from the project owner.

**Version**: 1.0.0 | **Ratified**: 2025-11-21 | **Last Amended**: 2025-11-21