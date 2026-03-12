# Governance

## Goals

LibreFang exists to maintain the codebase in the open, accept outside contributions on normal GitHub workflows, and preserve contributor credit.

## Decision-Making

- Day-to-day technical decisions are made in pull requests and issues.
- Maintainers are expected to explain design rejections with concrete technical reasons.
- Breaking governance changes should be proposed in a pull request against this file.

## Contribution Policy

- Accepted changes should land through GitHub merge or squash merge whenever possible.
- If a maintainer needs to adapt or rewrite a contributor's patch, the maintainer preserves attribution with commit metadata such as `Co-authored-by` and credits the contributor in release notes.
- Closing a pull request and re-implementing it privately without attribution is not acceptable project practice.
- Large design changes should start as an issue so contributors can align before doing heavy implementation work.

## Review Expectations

- New pull requests should receive an initial maintainer response within 7 days.
- If a pull request is blocked on architecture or scope, maintainers should say so explicitly.
- Stale pull requests may be closed after explanation, but contributors should be told the reason and the path to revive the work.

## Maintainers

- Repository maintainers are responsible for review quality, release management, and enforcing this governance document.
- Maintainers should avoid becoming a single-person bottleneck. When possible, at least two people should be able to review and release the project.
- Maintainer expectations and the current roster are tracked in [`MAINTAINERS.md`](MAINTAINERS.md).

## Security

Security reports use the private process in [`SECURITY.md`](SECURITY.md), not public issues.
