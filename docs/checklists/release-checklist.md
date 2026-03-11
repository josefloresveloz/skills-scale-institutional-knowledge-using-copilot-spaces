# Release Checklist

**Owner:** Release Manager  
**Purpose:** Ensure every release is completed safely, with clear communication and a tested rollback path.

---

## Pre-Release

- [ ] All required pull requests are merged and feature branches are deleted
- [ ] CI pipeline passes (build, lint, unit tests, integration tests)
- [ ] Release notes drafted and reviewed (includes new features, bug fixes, known issues)
- [ ] Rollback plan documented and communicated to the operations team
- [ ] QA Analyst has provided written sign-off (see [QA Checklist](./qa-checklist.md))
- [ ] Staging smoke tests completed successfully
- [ ] Release window communicated to stakeholders and support teams
- [ ] Feature flags and configuration changes verified for the target environment

## Post-Release

- [ ] Production smoke tests completed (critical user flows verified)
- [ ] Error rates and key metrics reviewed (no unexpected spikes)
- [ ] Stakeholder announcement sent (release notes, known issues, support contacts)
- [ ] Release notes published to the appropriate channel (docs, changelog, etc.)
- [ ] Any follow-up issues logged and triaged
- [ ] Rollback plan confirmed as no longer needed (or rollback executed if required)

---

> **Note:** This checklist is a lightweight starting point. Adapt it to your project's tooling and deployment cadence.
