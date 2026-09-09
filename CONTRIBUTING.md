# Contributing to YummYummy

## Workflow

Use short-lived branches from `main`:

- `feat/<name>` for product features
- `fix/<name>` for bug fixes
- `chore/<name>` for maintenance and tooling
- `docs/<name>` for documentation

Open a pull request back to `main`. Keep each pull request focused on one issue whenever practical.

## Issues

Issues should have:

- one primary `type:*` label;
- one `priority:*` label;
- one `weight:*` label;
- one primary `area:*` label;
- a milestone;
- explicit acceptance criteria;
- dependencies or blockers when applicable.

Weights use a small Fibonacci scale:

- `weight: 1`: very small, isolated change
- `weight: 2`: small change
- `weight: 3`: moderate change
- `weight: 5`: large change
- `weight: 8`: very large; split it when practical

## Commits

Prefer Conventional Commits:

- `feat: add recurring purchase rule`
- `fix: prevent duplicate shopping demand`
- `chore: update dependencies`
- `docs: document recipe matching`

## Releases

Releases follow Semantic Versioning and are created from tags matching `v*.*.*`.

The release workflow creates GitHub release notes automatically when a matching tag is pushed.
