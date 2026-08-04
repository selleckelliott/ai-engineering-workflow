# Agent Operating Rules

## Purpose

This repository defines reusable AI-assisted engineering workflows. It does not automatically govern any product repository.

## Adoption boundary

Do not add these protocols, skills, hooks, planning directories, or tooling to another repository unless that project's adoption has been discussed and explicitly approved.

## Working principles

- Preserve human control over scope, architecture, release decisions, and evidence.
- Inspect the current repository state before proposing or implementing changes.
- Separate planning, implementation, review, integration review, and release validation.
- Prefer small, dependency-aware increments with explicit completion conditions.
- Reuse valid evidence; do not recreate broad or retired test gates without a specific reason.
- Never expose secrets or request secret values in logs, plans, tickets, or handoffs.
- Record exact branches, commits, pull requests, and authoritative evidence when release work depends on them.
- Keep imported upstream skills pinned and review updates intentionally.

## Repository scope

This repository may contain:

- reusable skills and orchestration;
- planning and technical-design templates;
- Wayfinder adapters and conventions;
- review and handoff templates;
- upstream version records;
- project-neutral safety and evidence policies.

Project-specific facts belong in the project repository, not here.
