<p align="center">
  <img src="eudiplo.png" alt="EUDIPLO" width="360">
</p>

<p align="center">
  <b>Your diplomatic layer for EUDI Wallet integration</b><br>
  <a href="https://eudiplo.dev">Website</a> ·
  <a href="https://docs.eudiplo.dev">Documentation</a> ·
  <a href="https://discord.gg/58ys8XfXDu">Discord</a> ·
  <a href="https://github.com/EUDIPLO/eudiplo/releases">Releases</a>
</p>

EUDIPLO is open-source middleware that connects your backend to EUDI Wallets.
It issues and requests credentials over **OID4VCI** and **OID4VP**, supports
**SD-JWT VC** and **mDOC (ISO 18013-5)**, and exposes everything through a single
HTTP API, so you can integrate from any stack without handling the protocol and
cryptography yourself.

EUDIPLO is an [LF Decentralized Trust](https://www.lfdecentralizedtrust.org/)
project, licensed under Apache 2.0.

![EUDIPLO architecture overview](overview.svg)

## Repositories

| Repository | Description |
| --- | --- |
| [eudiplo](https://github.com/EUDIPLO/eudiplo) | The EUDIPLO service, web client, CLI, SDK and documentation |
| [governance](https://github.com/EUDIPLO/governance) | Teams and repository permissions for this organization |
| [.github](https://github.com/EUDIPLO/.github) | This profile and the default community files for all repositories |

## Try it

```bash
npx @eudiplo/cli demo
```

This starts the service and the web client locally with Docker. See the
[quick start](https://docs.eudiplo.dev/cookbooks/foundation) for other options.

## Get involved

- **Questions and help:** [Discord](https://discord.gg/58ys8XfXDu)
- **Bugs and feature requests:** [issues in the eudiplo repository](https://github.com/EUDIPLO/eudiplo/issues)
- **Community call:** bi-weekly on Thursdays,
  [join via Zoom](https://zoom-lfx.platform.linuxfoundation.org/meeting/94494306854?password=0d272140-5b2b-4bd4-a8fe-0b70efe1aa86)
- **Contributing:** read the [contribution guidelines](https://github.com/EUDIPLO/.github/blob/main/CONTRIBUTING.md)
- **Security issues:** report them privately as described in the
  [security policy](https://github.com/EUDIPLO/.github/blob/main/SECURITY.md)

## Governance

EUDIPLO is governed by its
[technical charter](https://github.com/EUDIPLO/eudiplo/blob/main/EUDIPLO%20Technical%20Charter%20(FINAL%2008.11.25).pdf).
See [GOVERNANCE.md](https://github.com/EUDIPLO/.github/blob/main/GOVERNANCE.md)
for how decisions are made and who maintains the project.
