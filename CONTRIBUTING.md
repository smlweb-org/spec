# Contributing

Thank you — the standard only improves through use and disagreement.

## The three most useful contributions

1. **A pilot report.** Implement a Sparse representation for one critical page, run [`sml-audit`](https://github.com/smlweb-org/sml-audit) against it, and post what happened — numbers, friction, surprises — in Discussions or via the *pilot report* issue template.
2. **A budget disagreement.** If a threshold (50 KB, 2 round trips, zero third-party scripts…) is wrong for a real case you have, say so with the evidence. Use the *budget disagreement* template.
3. **A spec edge case.** Authenticated pages, forms, equivalence, caching — if the spec is silent or ambiguous where you needed an answer, use the *spec edge case* template.

## Proposing spec changes

Open an issue or discussion before a pull request for anything normative — it saves everyone rework. Editorial fixes (typos, clarity) can go straight to PR. Normative text uses RFC 2119 keywords (MUST/SHOULD/MAY); keep additions as small as the idea allows.

## Scope guardrails

In scope: delivery profiles, negotiation, budgets, conformance, authoring guidance. Out of scope by design: gateways or proxies, separate content formats, anything that breaks end-to-end TLS, and negotiation signals that enlarge fingerprinting surface.

## Conduct

Be kind, be concrete, argue with evidence. We follow the spirit of the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/); report unacceptable behavior to the maintainers via the contact on smlweb.org.
