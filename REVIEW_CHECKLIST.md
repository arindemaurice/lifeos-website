# LIFEOS Review Checklist

Please review this ZIP as a **website direction and page-layout concept**, not as a claim that the full platform is finished.

## Visual review
- [ ] Overall look and feel
- [ ] Sidebar and page names
- [ ] Mobile layout
- [ ] Colors, spacing and typography
- [ ] Dashboard modules

## Product review
- [ ] Are these the right modules?
- [ ] What should be on the dashboard first?
- [ ] Which modules should share data?
- [ ] Which features should be postponed?
- [ ] Which real services should be integrated first?

## Build honesty
- [ ] Front-end interactions are labeled as local preview functionality.
- [ ] No real account, AI, payment, database or cloud sync is claimed.
- [ ] No secret API keys are included.
- [ ] Dummy metrics are avoided; decorative chart bars are labeled.

## Suggested next milestone
After approving the page structure, create a real application repository with a database schema, authentication, API contracts, migrations, tests and deployment setup. Build one end-to-end vertical slice first (for example, account + task CRUD + PostgreSQL), then reuse that pattern for other modules.
