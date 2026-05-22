---
name: Maintenance task
about: Track a maintenance, refactor, dependency upgrade, or housekeeping task
title: 'Maintenance: <short summary of the task>'
labels: ['maintenance', 'needs-triage']
assignees: ''
---

## Maintenance Task

Use this template for housekeeping work — refactors, dependency upgrades,
test infrastructure, tooling, or tech-debt cleanup. The Issue Management
Automation workflow will detect "maintenance" in the title and apply the
`maintenance` label automatically.

### Motivation

Why is this work needed? (e.g. tech debt, deprecated dependency, security
patch, performance regression, developer-experience improvement.)

### Scope

What exactly will change? List the files, modules, or systems involved.

### Risks / breaking changes

- [ ] No breaking changes expected
- [ ] May require a coordinated release
- [ ] Changes public API / configuration / behaviour

### Validation plan

How will we verify this maintenance task didn't regress anything?
(unit tests, integration tests, manual smoke test, CI lint, …)

### Priority hints (optional)

Use **low**, **minor**, or **nice-to-have** for `priority-low`. Use
**important**, **high**, or **blocking** for `priority-high`. Otherwise the
automation will default to `priority-medium`.

### Additional context

Links to upstream issues, release notes, advisories, or related PRs.
