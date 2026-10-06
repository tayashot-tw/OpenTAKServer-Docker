# Changelog

## Unreleased — source publication repair

- Restore DSM deployment and registration portal source from the published v1.1.0 ZIP (SHA-256: 300f5739a54200e6c0da757a4326bb02ec81b4c0094c8d8dc4d0e6e4269a00db).
- Publish GPL-3.0 license, upstream attribution, setup script and environment example in the default branch.
- Add CI for Python/Shell syntax, Compose configuration, source hygiene and local README links.

This restores the published release source; it does not certify current NAS deployment fixes. Portal administrator 2FA interoperability remains unverified. Upstream images track mutable tags. Validate deployment and authentication before production use.

## v1.1.0 — 2026-10-04

Initial published Synology DSM package with registration, approval, groups and certificate/package delivery.
