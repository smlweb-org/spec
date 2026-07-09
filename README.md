# S—ML Web · spec

**S—ML Web: Responsive Delivery Profiles for the Open Web.** One URL serves the same canonical content in three weights — **S (Sparse)**, **M (Medium)**, **L (Luxe)** — negotiated over HTTP by network conditions, device capability, and consumer type, including AI agents. Not a new protocol or framework: a testable contract on ordinary URLs, HTML, HTTP, and TLS.

> One URL. Three weights. No separate internet.

This repository is the canonical home of the standard.

## Contents

- [`spec.md`](spec.md) — **S—ML Web Profile 0.1** (draft): the normative text. Profile identifiers, discovery, negotiation, Sparse requirements, budgets, content equivalence, hydration, conformance, security & privacy.
- [`paper.md`](paper.md) — the position paper: full rationale, hydration model, AI consumption, sector cases (satellite/NTN, aviation, roaming), sustainability, and the human argument.
- [`GOVERNANCE.md`](GOVERNANCE.md) — how the spec evolves and where it is headed.
- [`CONTRIBUTING.md`](CONTRIBUTING.md) — how to propose changes, report pilots, and disagree productively.

Website: **https://smlweb.org** · Auditor: [smlweb-org/sml-audit](https://github.com/smlweb-org/sml-audit) · Agent skills: [smlweb-org/skills](https://github.com/smlweb-org/skills)

## The contract in one table

| Requirement | s | m | l |
|---|---|---|---|
| Initial payload (HTML + render-blocking subresources) | ≤ 50 KB | ≤ 500 KB | open |
| Core content without JavaScript | MUST | SHOULD | MAY |
| Third-party scripts | MUST NOT | ≤ 5 hosts | open |
| Custom fonts | SHOULD NOT | MAY | MAY |
| Round trips before core content | ≤ 2 | ≤ 5 | open |
| Machine-readable summary | MUST | SHOULD | SHOULD |
| End-to-end TLS | MUST | MUST | MUST |

## Participate

- **Pilot it**: implement a Sparse representation for one critical page, audit it, and share the result in [Discussions](../../discussions).
- **Disagree with the budgets**: that feedback is explicitly wanted — use the *budget disagreement* issue template.
- **Found an edge case** the spec doesn't cover? Use the *spec edge case* template.

## About this repository

Public. Discussions enabled — that is the community's main venue. Issues use the templates in `.github/ISSUE_TEMPLATE/`. The `main` branch is protected; spec changes land by pull request and are recorded per version.

## License

Text of the specification and paper: [CC BY 4.0](LICENSE.md).
