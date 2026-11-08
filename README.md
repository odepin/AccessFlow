# AccessFlow

> Guided accessibility QA for fictional shopping journeys.

**Current state:** Documentation starter / proposed product. The presence of this README does **not** mean the software has been implemented, deployed, used. Update this status to reflect real work.

## What it is

AccessFlow is a proposed specialist software tool for E-commerce engineering teams, auditors, and small accessibility consultancies. Individual automated scans do not capture the complete usability of multi-step keyboard and screen-reader journeys. The intended differentiation is: Repeatable manual-plus-automated test recipes focused on checkout flows, not unsupported one-click compliance scoring.

## Intended users and use cases

- Navigate a sample checkout with keyboard-only interactions
- Detect focus loss after a synthetic modal dialog closes
- Complete a manual review and export observed barriers

## Planned features

- Define reusable scenario scripts for search, cart, and checkout steps
- Run non-destructive automated keyboard/focus and semantic checks on demo pages
- Record manual reviewer decisions without end-user personal data
- Capture step-by-step evidence from synthetic storefront fixtures
- Export accessible HTML test reports with clear manual-test limitations

## Proposed technology

TypeScript, Playwright, Node.js, Vitest, static HTML report generator

These technologies are *planned*, not a claim that dependencies have already been installed or code has been written. Revise this section when actual implementation decisions are made.

## Proposed architecture

- Declarative journey specification
- Playwright runner against local sample storefront
- Manual inspection questionnaire
- Static report generator

See [TECHNICAL_PLAN.md](TECHNICAL_PLAN.md) for technical boundaries and acceptance tests.

## Running locally

**Not yet runnable.** This package contains documentation templates, not software. When a functioning implementation is available, replace this paragraph with tested prerequisites, install instructions, a verified executable command, and a reproducible example using `Local fake storefront with fake products, addresses, and orders.`

## Data boundaries and exclusions

Crawling live customer accounts, real purchases, real payment data, or certifying WCAG compliance automatically. All public examples should use Local fake storefront with fake products, addresses, and orders.

## Known limitations / validation risks

Accessibility cannot be determined solely by automation; keep explicit human review steps and source-linked criteria.

## Development roadmap

Work is broken into estimated, not-yet-completed milestones in [ROADMAP.md](ROADMAP.md). They are *planning estimates*, not an assertion that development has begun or that work will definitely be performed.

## Business direction

Potential commercial extensions: Team workflows, test library packs, and CI integrations. 

## Contributing and licensing

License: [Mozilla Public License 2.0](LICENSE) (`MPL-2.0`). The distribution contains the complete license text. Any future source files can include the SPDX identifier `MPL-2.0` and the Exhibit A notice where appropriate. Rights in contributions and project ownership must be verified before licensing.

