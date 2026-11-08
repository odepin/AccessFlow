# AccessFlow - technical plan

**Planning document, not an implementation report.**

## Product objective

Repeatable manual-plus-automated test recipes focused on checkout flows, not unsupported one-click compliance scoring.

## Intended system boundary

- **Input:** Local fake storefront with fake products, addresses, and orders.
- **Processing stages:** Declarative journey specification; Playwright runner against local sample storefront; Manual inspection questionnaire; Static report generator.
- **Output:** A repeatable run demonstrates known accessibility defects and generates evidence.
- **Runtime / build stack (tentative):** TypeScript, Playwright, Node.js, Vitest, static HTML report generator
- **Explicitly excluded:** Crawling live customer accounts, real purchases, real payment data, or certifying WCAG compliance automatically.

## Functional modules

- Define reusable scenario scripts for search, cart, and checkout steps
- Run non-destructive automated keyboard/focus and semantic checks on demo pages
- Record manual reviewer decisions without end-user personal data
- Capture step-by-step evidence from synthetic storefront fixtures
- Export accessible HTML test reports with clear manual-test limitations

## Demonstration and acceptance cases

**Test 1:** Navigate a sample checkout with keyboard-only interactions

**Test 2:** Detect focus loss after a synthetic modal dialog closes

**Test 3:** Complete a manual review and export observed barriers

## Safety, privacy, and provenance

1. Keep example datasets fictional, self-created, or appropriately licensed.
2. Run locally for the initial prototype; do not collect data on actual third parties.
3. Document origin and versions of external specifications and dependencies.
4. Exclude production credentials; put environment variable *names* only in `.env.example` if required later.
5. Do not make certification, legal compliance, professional safety, or performance guarantees without independent validation.

## Engineering unknowns and constraints

Accessibility cannot be determined solely by automation; keep explicit human review steps and source-linked criteria.

## Release definition

A first release requires a runnable prototype, verified README instructions, automated tests tied to the three demonstrations, the full LICENSE file, and an honest public GitHub development history. The roadmap estimates are hypotheses until reviewed during implementation.
