# Public / Private Security Boundary

This repository is intentionally a **public-safe commercial surface**. It demonstrates the problem domain, architectural intent, evaluation model, and selected interfaces without disclosing the private production substrate.

## Public-safe material

Material may be published here when disclosure does not materially weaken the private control plane. Examples include:

- architectural problem statements and threat-model framing
- high-level trust and authority boundaries
- non-secret interface definitions
- simulated adapters and test doubles
- sanitized diagrams and evaluation criteria
- CI evidence that does not disclose proprietary implementation
- public program summaries and non-confidential technical briefs

## Private material

The following remain outside this public repository unless explicitly approved for release after review:

- production cryptographic envelope implementation
- private key lifecycle and rotation mechanics
- secrets, credentials, tokens, signing material, or deployment configuration
- proprietary substrate implementation
- entitlement and license-enforcement internals
- private operational telemetry or customer information
- exploit-sensitive details that would materially reduce system security
- source, schemas, or workflows designated as private in the commercial vault

## Release gate

Before material moves from the private vault to this public showroom, review it for:

1. authorization to disclose
2. third-party license and attribution obligations
3. secrets and sensitive data
4. security impact and attack-surface expansion
5. founder provenance and document lineage
6. commercial value leakage
7. consistency with executed NDAs, evaluation agreements, and customer obligations

A rights/documentation gap should be recorded and resolved as a bounded issue. It does not erase founder provenance.

## Reporting

For security-sensitive inquiries, contact [tokencraft1390@gmail.com](mailto:tokencraft1390@gmail.com). Do not publish suspected vulnerabilities or private implementation details in a public issue.
