# Dependency Compatibility

This matrix is generated from the validation-branch dependency declarations.
Release managers should review exceptional exclusions with the owning team.

<!-- compatibility:start -->
| Component | Supported versions | Exclusions | Support tier |
|---|---|---|---|
| api-gateway | >=2.8,<3.2 | 3.0.0-rc1 | standard |
| event-router | ^5.3 | 5.4.2|linux | critical |
| legacy-bridge | >=1.9,<2.0 | none | maintenance |
<!-- compatibility:end -->

## Interpretation notes

Ranges are consumed by deployment validation; support tiers control escalation routing.
The prose in this document is maintained manually and must not be replaced.
