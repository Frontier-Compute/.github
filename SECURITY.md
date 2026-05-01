# Security Policy

Frontier Compute treats security reports as private by default.

## Reporting

Please do not open public issues for vulnerabilities, exploit details, proof-of-concept code, secrets, keys, or production paths.

Preferred channels, in order:

1. GitHub Private Vulnerability Reporting on the affected repository, when available.
2. A private GitHub security advisory or private issue created by the maintainers.
3. Direct private handoff to a Frontier Compute maintainer if GitHub private reporting is not available.

If you are unsure which repository is affected, start with a short private report that names the component and impact class, without public reproduction details.

## Scope

This policy covers public repositories under `Frontier-Compute` and security-relevant public infrastructure operated by Frontier Compute.

Out of scope unless explicitly authorized:

- Testing against production services with destructive, high-volume, persistence, social engineering, spam, phishing, or denial-of-service methods.
- Attempts to access, move, or exfiltrate user funds, credentials, private keys, seeds, tokens, customer data, or operator-only systems.
- Public disclosure before maintainers have had a reasonable chance to investigate and remediate.

## Report Contents

Useful private reports include:

- affected repository, service, route, or component
- affected version or commit when known
- impact summary
- minimal local reproduction steps
- expected versus actual behavior
- patch sketch or mitigation idea when available

Keep reports minimal and private. Do not include unrelated secrets, customer data, or broad scans.

## Coordinated Disclosure

We will preserve the original report timestamp and private channel context when moving a report into a durable GitHub advisory or private issue. Public credit and disclosure timing should be coordinated with maintainers after remediation.
