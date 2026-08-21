# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management framework. This directory contains comprehensive guidance for running projects across OctoAcme, from initial concept through delivery and retrospectives. Use these docs as your single source of truth for process, roles, and templates.

## Overview

OctoAcme runs projects with a clear, staged lifecycle that begins with a lightweight initiation and moves through planning, execution, release, and retrospective. Projects are kicked off with a one‑pager capturing the problem, objective, success metrics, stakeholders, and a high‑level timeline; that one‑pager and a simple decision gate determine whether work moves into detailed planning. Planning produces a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a release/milestone map. Day‑to‑day work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and by small, focused pull requests that link to issues and include acceptance criteria.

Roles and ownership are explicit: each project has a named Project Manager (coordinating delivery and risks) and Product Manager (defining outcomes and prioritization), with Developers and QA handling implementation, testing, and validation. Risk management is formalized with a simple Risk Register (ID, description, impact, likelihood, owner, mitigation, status) and a clear escalation path from team → PM → Product Lead → Sponsor. Communication templates and escalation paths are included so teams can keep stakeholders informed and act quickly on blockers or incidents.

Communication follows a predictable cadence to keep stakeholders aligned and surface blockers early: daily standups for progress and impediments, a weekly delivery sync and PM–PdM alignment, scheduled demos at the end of sprints or milestones, and monthly stakeholder briefings. CI and automated checks gate code review, with unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in pipelines, and manual QA for feature acceptance when necessary. Releases use a deployment checklist, staged verification, and a rollback playbook to reduce production risk.

## Quick Start (when to use each doc)

- Project Initiation: ./octoacme-project-initiation.md  
  When: for new project ideas or feature proposals. Use to validate business need and align stakeholders.

- Project Planning: ./octoacme-project-planning.md  
  When: after initiation approval. Use to break work into shippable increments, estimate, and plan releases.

- Execution & Tracking: ./octoacme-execution-and-tracking.md  
  When: during active development. Use to manage the team rhythm, PR practices, and progress tracking.

- Risk Management & Communication: ./octoacme-risks-and-communication.md  
  Use across the lifecycle for risk register, escalation, and stakeholder updates.

- Release & Deployment: ./octoacme-release-and-deployment.md  
  When: ready to promote changes to production. Use for release checklists, rollbacks, and incident handling.

- Retrospective & Continuous Improvement: ./octoacme-retrospective-and-continuous-improvement.md  
  When: after sprints, releases, or incidents. Use to capture learnings and create action items.

- Roles & Personas: ./octoacme-roles-and-personas.md  
  Reference guide for responsibilities and communication patterns for Developers, Product Managers, and Project Managers.

## OctoAcme Principles

- Customer-first: prioritize customer value and usability  
- Iterative delivery: deliver small, testable increments  
- Clear ownership: each project has a named PM and Product Lead  
- Data-informed decisions: measure impact and iterate based on evidence  
- Psychological safety: encourage feedback and learning

## How to Contribute

To request updates, clarifications, or new content for these process docs, please create an issue using the Process Doc Update template: ../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
