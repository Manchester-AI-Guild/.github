<!--
  Design notes (17 September 2026).
  Taken from github.com/Resourcio-Community/AI-ML-Resources: categorised link tables with
  fixed columns and a link column per row; emoji-led section headings.
  Taken from github.com/Resourcio-Community/Resourcio_Community-Website: centred logo header
  with a shields.io badge row under it, section icons and a "Getting involved" style
  contributing section.
-->

<p align="center">
  <a href="https://www.manchesteraiguild.org/"><img src="https://avatars.githubusercontent.com/u/319570462?v=4" alt="Manchester AI Guild" width="120"></a>
</p>

<h1 align="center">Manchester AI Guild organization</h1>

<p align="center">The GitHub organization profile and the default community-health files every Manchester-AI-Guild repository inherits.</p>

<p align="center">
  <a href="https://github.com/Manchester-AI-Guild/.github/actions/workflows/security-checks.yml"><img src="https://github.com/Manchester-AI-Guild/.github/actions/workflows/security-checks.yml/badge.svg" alt="Security Checks"></a>
  <img src="https://img.shields.io/badge/Council--owned-Manchester%20AI%20Guild-F2C230" alt="Council-owned">
  <img src="https://img.shields.io/badge/Branch-main%20only-2563EB" alt="main only">
</p>

This repository stores the GitHub organization profile and the default community-health configuration for the Manchester AI Guild.

## 🗂️ What's here

| | File | What it is |
|---|---|---|
| 🏛️ | [`profile/README.md`](profile/README.md) | The organization profile shown at [github.com/Manchester-AI-Guild](https://github.com/Manchester-AI-Guild) |
| 🤝 | [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | Mirror of the canonical Code of Conduct (source: operations repository `policies/code-of-conduct.md`) |
| 📝 | [`CONTRIBUTING.md`](CONTRIBUTING.md) | Default contributing guide for every Guild repository |
| 🛡️ | [`SECURITY.md`](SECURITY.md) | How to report a vulnerability |
| 🧾 | [`ISSUE_TEMPLATE/`](ISSUE_TEMPLATE/), [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) | Default bug report, feature request and pull request templates |
| 👤 | [`.github/CODEOWNERS`](.github/CODEOWNERS) | Default code owners |
| ✅ | [`.github/workflows/security-checks.yml`](.github/workflows/security-checks.yml) | Security Checks: gitleaks `secret-scan` on every push and pull request |

## 🎯 Purpose

This repo is the org-level configuration layer for:
- the public organization profile
- default community guidance and contributor standards
- issue and PR templates
- security reporting and repo hygiene defaults
- shared org-level documentation and references

## 📚 Guild repositories

| | Repository | Visibility | What it holds |
|---|---|---|---|
| 🏠 | [manchester-ai-guild](https://github.com/Manchester-AI-Guild/manchester-ai-guild) | Public | Public projects, working groups, and community collaboration: mission, purpose statement, operating model, participants, docs microsite |
| 🌐 | [website](https://github.com/Manchester-AI-Guild/website) | Private | Source of [www.manchesteraiguild.org](https://www.manchesteraiguild.org/) and the draft policy register |
| 🎨 | [assets](https://github.com/Manchester-AI-Guild/assets) | Private | Official brand assets; only verified Council members publish with them |
| 🔒 | [manchester-ai-guild-operations](https://github.com/Manchester-AI-Guild/manchester-ai-guild-operations) | Private | Member-only planning, minutes, runbooks and the canonical policy sources |
| ⚙️ | [.github](https://github.com/Manchester-AI-Guild/.github) | Public | This repository |

## 📜 Policies

Draft Guild policies are registered in the website repository at [`docs/policies/README.md`](https://github.com/Manchester-AI-Guild/website/blob/main/docs/policies/README.md) (private repository, members only); their status is **Draft, awaiting Council 10 Oct 2026**. The Code of Conduct here is a mirror of the canonical file in the operations repository; edit the canonical file and copy it here.

## 🏛️ Council and owners

The Guild Council was proposed at the 28 August meeting and reviewed again at the 4 September Council meeting. The public roster is [participants-and-ecosystem.md](https://github.com/Manchester-AI-Guild/manchester-ai-guild/blob/main/docs/participants-and-ecosystem.md).

| Name | Council role |
|---|---|
| Adrian Quayle | President |
| Mihran Hovnanian | Acting Chairman & Secretary |
| Edwin Luther | Governance & Ethics; owner of this repository |
| Simon Ellis | Engagement & Projects Lead |
| Fernando Torres | Community Lead & Events |
| Trevor Roberts | AI Readiness Assessment Lead |
| TBC | Treasurer (open) |
| TBC | Marketing & Communications (open) |

## 🛡️ Security and governance

This repository is for org-level defaults and profile content only. It should not be used for storing secrets, credentials, or sensitive project data.

## 🤝 How to contribute

- **Change a default file or the profile**: open a pull request against `main`; the `secret-scan` check must pass before merge. Changes here apply to every Guild repository that does not override the file.
- **Report a bug or suggest a feature** in any Guild repository using the templates in [`ISSUE_TEMPLATE/`](ISSUE_TEMPLATE/).
- **Report a security problem**: follow [`SECURITY.md`](SECURITY.md); do not open a public issue.
- **Code of Conduct**: applies to all Guild spaces; see [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md).

## 📁 Repository

- Purpose: organisation profile (`profile/README.md`) and default community-health files (Code of Conduct, contributing guide, security policy, issue and PR templates) inherited by every Manchester-AI-Guild repository.
- Owner: Edwin Luther — Council, Governance & Ethics
- Policies index: [website `docs/policies/README.md`](https://github.com/Manchester-AI-Guild/website/blob/main/docs/policies/README.md) (private repository, members only)
- Only `main` exists; changes go through pull requests and the `secret-scan` check.
