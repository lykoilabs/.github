<!--
External pull requests are not being accepted yet (see CONTRIBUTING.md).
This template is for maintainers and invited contributors.
-->

## What

One or two sentences: what changes and why. Link the issue or ADR.

## How

Anything a reviewer needs to know about the approach that is not obvious
from the diff. Note any ADR this touches or supersedes.

## Checklist

- [ ] `cargo fmt --all --check`, `cargo clippy --workspace --all-targets -- -D warnings`, `cargo test --workspace` and `cargo deny check` pass locally
- [ ] New behaviour has tests; simulation changes keep determinism (no wall clock, no map-order dependence)
- [ ] Docs and ADRs updated where behaviour or decisions changed
- [ ] No game client material, no copyleft-derived code, no new non-permissive dependency
- [ ] Commit messages follow Conventional Commits, explain *why*, and carry the coding-agent credit footer where applicable
