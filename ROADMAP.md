# AccessFlow - development roadmap

**Status:** Planned work only. None of the boxes are marked completed. 

## Product-level acceptance criterion

A repeatable run demonstrates known accessibility defects and generates evidence.

## Estimated work breakdown

| Step | Milestone | Estimated hours | Observable outcome |
|---|---|---:|---|
| 1 | Design synthetic storefront and scenario format | 9 | A complete offline shopping journey fixture |
| 2 | Implement scenario executor | 11 | Reliable step and selector handling |
| 3 | Add targeted automated assertions | 10 | Focus/label/contrast-related hints with bounded claims |
| 4 | Build manual review capture | 8 | Reviewers can record step-specific observations |
| 5 | Generate accessible reports | 8 | Static report explains outcomes and limitations |
| 6 | Tests, documentation, CI | 10 | Stable end-to-end fixture runs |
| | **Total estimated** | **56** | |

## Detailed milestones

### 1. Design synthetic storefront and scenario format (9 estimated hours)

- [ ] Deliverable: A complete offline shopping journey fixture.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 2. Implement scenario executor (11 estimated hours)

- [ ] Deliverable: Reliable step and selector handling.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 3. Add targeted automated assertions (10 estimated hours)

- [ ] Deliverable: Focus/label/contrast-related hints with bounded claims.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 4. Build manual review capture (8 estimated hours)

- [ ] Deliverable: Reviewers can record step-specific observations.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 5. Generate accessible reports (8 estimated hours)

- [ ] Deliverable: Static report explains outcomes and limitations.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 6. Tests, documentation, CI (10 estimated hours)

- [ ] Deliverable: Stable end-to-end fixture runs.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

## QA and release gates

- [ ] A real runnable implementation exists, with verified setup commands in `README.md`.
- [ ] Automated tests pass in a clean environment and failures are actionable.
- [ ] Only fabricated, original, openly licensed, or otherwise authorized sample data is published.
- [ ] No passwords, API keys, secrets, customer records, or employer/client confidential artifacts appear in repository history.
- [ ] A source-linked change log and actual progress notes distinguish finished work from plans.
- [ ] The GitHub history preserves authentic work and authorship; do **not** manufacture or backdate commits.

## Parking lot and risks

- Technical: Accessibility cannot be determined solely by automation; keep explicit human review steps and source-linked criteria.
- Commercial hypothesis (not validated): Team workflows, test library packs, and CI integrations.
- Beyond MVP: defer paid extensions and hosted features until the underlying product works.
