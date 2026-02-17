# Definition of Done (Repo Standard)

## Must Have
- [ ] Setup is reproducible using docs/01_setup.md
- [ ] No secrets committed (only config/.env.example)
- [ ] Changes tracked in CHANGELOG.md
- [ ] Top 5 failure cases in docs/03_troubleshooting.md
- [ ] Security baseline in docs/04_security.md

## Ops Projects (if relevant)
- [ ] Backup procedure exists and is tested
- [ ] Restore procedure exists and is tested
- [ ] Update procedure exists
- [ ] Rollback plan documented

## Hardware Projects (if relevant)
- [ ] Safety defaults: OFF is safe state
- [ ] E-STOP / Guards documented
- [ ] Wiring diagram saved in docs/diagrams/

## Done Means
- It runs reliably without babysitting
- I can rebuild it from the docs
