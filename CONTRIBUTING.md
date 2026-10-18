# Contributing to Lykoi Labs projects

Thanks for your interest. This page applies to every repository under the
`lykoilabs` organisation unless a repository says otherwise.

## Current status: issues yes, pull requests not yet

The projects are pre-alpha and the architecture is still moving quickly.
Right now we:

- **welcome** bug reports, design questions, benchmarks and corrections to
  documentation, as issues;
- **do not accept** external pull requests. Unsolicited PRs will be closed
  with thanks; the ideas in them may still be picked up with credit.

This will change once the first playable milestone of Tenshu is out and the
public API has settled. The contributor agreement model (DCO sign-off is the
likely choice) will be announced then.

## Licensing

Everything in the organisation is licensed under the **MIT license**.
Unless you explicitly state otherwise, any contribution intentionally
submitted for inclusion in a project by you is licensed as above, without
any additional terms or conditions.

## Commit messages

Commits follow [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/):
`<type>(<optional scope>)[!]: <description>` with types `feat`, `fix`,
`docs`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`. Breaking
changes carry `!` and a `BREAKING CHANGE:` footer. The body explains why.

## Clean-room rules

These are not negotiable, and they apply to issues and discussions as much
as to code:

1. **No game client material.** Do not post or submit packet captures,
   opcode tables dumped from clients, asset or map data, encryption keys,
   decompiled or disassembled code, reflection dumps, or anything else
   derived from a game client you do not own the rights to.
2. **No copyleft-derived code.** Do not port, paraphrase or "translate" code
   from GPL, LGPL or AGPL projects (server emulators included) into any
   repository here. Describing how a system behaves is fine; its code is
   not.
3. **Permissive dependencies only.** New dependencies must be MIT,
   Apache-2.0, BSD, ISC, Zlib or similar. CI enforces this with
   `cargo deny`.

If you are unsure whether something crosses a line, ask in an issue before
posting it.

## Reporting bugs

Use the bug report template. Include the crate or binary and version, your
platform, what you did, what happened and what you expected. Logs and
reproduction steps help far more than screenshots.

## Security issues

Do not open an issue. See [SECURITY.md](SECURITY.md).

## Code of conduct

Participation is governed by the
[Contributor Covenant 2.1](CODE_OF_CONDUCT.md).
