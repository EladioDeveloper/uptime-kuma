# Security Policy

## Reporting a Vulnerability

Private vulnerability reporting is the only channel: create a new security advisory in
https://github.com/louislam/uptime-kuma/security/advisories/new and include a working PoC.
Reports without a PoC, or with an LLM-written description, are closed without reply.

Never open a public issue or discussion with the details of a vulnerability.

## Response Timeline

| Step                                 | Target                             |
| ------------------------------------ | ---------------------------------- |
| Triage of reports that include a PoC | 7 days                             |
| Fix for critical/high severity       | 30 days                            |
| Fix for medium/low severity          | 90 days                            |
| Public advisory with a CVE ID        | When the fixed version is released |

If a report with a PoC gets no answer within 14 days, you may mention the advisory ID (only the ID)
in a new issue so a maintainer can find it.

## Will be Closed without explanation

- No LLM description, I don't read it
- Do not report any upstream dependency issues, unless you have PoC to prove that the upstream issue affected Uptime Kuma.
- Do not report any scan result by any tools, unless you have PoC.
- Do not report any SSRF issues.

## Do you accept other 3rd-party bug bounty platforms?

At this moment, I DO NOT accept other bug bounty platforms, because I am not
familiar with these platforms and someone has tried to send a phishing link to
me by doing this already. To minimize my own risk, please report through GitHub
Advisories only. I will ignore all 3rd-party bug bounty platforms emails.

## Supported Versions

### Uptime Kuma Versions

You should use or upgrade to the latest version of Uptime Kuma.
All versions are upgradable to the latest version.

### Upgradable Docker Tags

| Tag             | Supported          |
| --------------- | ------------------ |
| 2               | :white_check_mark: |
| 2-slim          | :white_check_mark: |
| next            | :white_check_mark: |
| next-slim       | :white_check_mark: |
| 2-rootless      | :white_check_mark: |
| 2-slim-rootless | :white_check_mark: |
| 1               | ❌                 |
| 1-debian        | ❌                 |
| latest          | ❌                 |
| debian          | ❌                 |
| All other tags  | ❌                 |
