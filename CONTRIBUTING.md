# Contributing to EUDIPLO

Thanks for your interest in contributing! These rules apply to all repositories
in the [EUDIPLO organization](https://github.com/EUDIPLO). A repository can
have its own `CONTRIBUTING.md` with setup instructions and additional rules;
the
[EUDIPLO service](https://github.com/EUDIPLO/eudiplo/blob/main/CONTRIBUTING.MD)
does.

## Issues

- Search the existing issues before you open a new one.
- Include the version you use, your environment, steps to reproduce, and logs
  with secrets and personal data removed.
- For a feature request, describe the problem you want to solve before the
  solution you have in mind.
- Report security vulnerabilities privately as described in the
  [security policy](SECURITY.md), never in a public issue.

## Commits

Every commit must:

- carry a **DCO sign-off** (`Signed-off-by:` trailer), certifying the
  [Developer Certificate of Origin](https://developercertificate.org/). Add it
  with `git commit -s`.
- be **cryptographically signed** (GPG, SSH or S/MIME) so GitHub shows it as
  verified, for example with `git commit -S -s`.

To fix the last commit: `git commit --amend -S -s --no-edit`. For several
commits: `git rebase --signoff -S <base>`.

Commit messages follow
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
(`feat: …`, `fix: …`, `docs: …`, …). Releases are derived from them, so mark
breaking changes with `!` in the header and a `BREAKING CHANGE:` footer that
says what users must do.

## Pull requests

- Open pull requests against `main` and keep each one focused on one topic.
- For larger changes, open an issue first so the approach can be agreed on
  before you invest time.
- Make sure tests, linting and formatting pass, and update the documentation
  that describes the changed behavior.
- A maintainer of the repository reviews and merges the pull request.

## Getting help

Ask on [Discord](https://discord.gg/58ys8XfXDu) or join the community call; see
[SUPPORT.md](SUPPORT.md).

## Code of Conduct

All contributors follow the [Code of Conduct](CODE_OF_CONDUCT.md).
