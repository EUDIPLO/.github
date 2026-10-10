# Security Policy

This policy applies to all repositories in the
[EUDIPLO organization](https://github.com/EUDIPLO), unless a repository has its
own `SECURITY.md`.

## Supported Versions

We release security fixes for the latest release of each project. Older
releases do not receive patches; upgrade to the latest release to get fixes.

## Reporting a Vulnerability

Please report vulnerabilities privately. Do **not** disclose them in public
issues, pull requests or chat channels.

1. **GitHub private vulnerability reporting (preferred):** open the
   **Security** tab of the affected repository and choose
   **Report a vulnerability**. For the EUDIPLO service, use
   [this form](https://github.com/EUDIPLO/eudiplo/security/advisories/new).
2. **Email:** write to the LF Decentralized Trust security team at
   [security@lists.lfdecentralizedtrust.org](mailto:security@lists.lfdecentralizedtrust.org)
   with the subject `[SECURITY] <repository>: <brief description>`.

### What to include

- Type and severity of the issue (for example authentication bypass, injection,
  cryptographic flaw or credential disclosure)
- Affected repository, package and version(s)
- Location of the affected code (tag, branch, commit or file link)
- Steps to reproduce, and a minimal proof of concept if possible
- Impact and possible exploitation scenarios
- Suggested fixes or mitigations, if any
- How we can reach you for follow-up

### What to expect

- **Acknowledgment** within 3 business days
- **Triage**, including a first severity assessment, within 10 business days
- **Regular updates** while we work on a fix
- **Coordinated disclosure:** the fix is released together with a GitHub
  security advisory and, where applicable, a CVE

With your permission, we credit you in the advisory and the release notes.

## Scope

Out of scope are vulnerabilities in third-party dependencies (report them to
their maintainers; tell us if EUDIPLO is affected), issues in forks, and social
engineering attacks.
