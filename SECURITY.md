# Security policy

This repository is used for organization-level configuration, profile content, and default community health files for the Manchester AI Guild.

## Reporting a vulnerability

If you believe you have found a security vulnerability in a repository under the Manchester AI Guild organization, please report it responsibly and privately.

Please use GitHub private vulnerability reporting for the affected repository where available, or contact the maintainers through the agreed private channel for the Guild.

Do not disclose a vulnerability publicly until a fix is agreed and deployed.

## Responsible disclosure expectations

- provide a concise description of the vulnerability and the impact
- include reproduction steps where possible
- do not expose credentials, tokens, or personal data
- allow reasonable time for triage, remediation, and release planning before public disclosure

## Security baseline

The Guild should maintain a practical baseline across public and private repositories:

- keep sensitive operational work in private repositories
- protect protected branches with pull-request requirements
- enable secret scanning and push protection where supported
- review dependency updates and dependency vulnerability alerts
- do not commit secrets, API keys, or credentials

## Sensitive data

Do not commit or store:
- API keys or tokens
- cloud credentials
- personal data without explicit need
- customer or member data not approved for sharing

If a project contains sensitive information, keep it in a private repository with access limited to approved members only.
