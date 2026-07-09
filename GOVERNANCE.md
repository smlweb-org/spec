# Governance

S—ML Web is developed in the open, in deliberate stages.

## Current stage: community specification

The specification is maintained in this repository by its **editor** (the project originator), with changes proposed and discussed publicly. The editor's role is to keep the spec coherent, small, and implementable — not to be its only author. Substantive changes (budgets, header semantics, conformance rules) are announced in Discussions before merging so implementers can object.

## Decision principles

1. **Implementations over opinions.** Feedback grounded in a real deployment or pilot outweighs theoretical preference.
2. **The budgets are the standard.** Thresholds may change through evidence and discussion; the existence of testable budgets may not.
3. **Never fork the web.** Any proposal that requires a gateway, a separate content ecosystem, or breaking end-to-end security is out of scope by design.
4. **Small spec, strong tests.** Anything that can live in tooling or guidance instead of normative text, should.

## Roadmap

1. **Now** — community spec + reference tooling, iterated through real deployments.
2. **Next** — a W3C Community Group, once 2–3 independent pilots exist, to widen stewardship without stalling momentum.
3. **Then** — formal standards-track submission when multiple independent implementations exist: the profile vocabulary and discovery toward W3C; the `Accept-Profile` / `Content-Profile` / `Available-Profiles` headers likely via the IETF HTTP Working Group.

## Versioning

The spec uses simple numbered profiles (`0.1`, `0.2`, …). Breaking changes to normative requirements bump the version; editorial fixes do not. Each version is tagged in this repository.
