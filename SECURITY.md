# Security Policy — MrPress LLC

> © 2025 MrPress LLC. All Rights Reserved.

## Overview

MrPress LLC takes the security of its software, website, and digital assets
seriously. This document outlines our security policy, including how to report
a potential security vulnerability, what to expect after submitting a report,
and the scope of issues we consider in scope for reporting.

While this repository hosts a static HTML website with no backend, no
database, and no user authentication system, we still encourage responsible
disclosure of any security concerns related to the hosted site or this
repository.

---

## Supported Versions

MrPress LLC maintains and supports only the most current version of the
software in this repository. Security fixes are applied to the current version
only. Prior versions are not maintained.

| Version | Status          |
|---------|-----------------|
| 1.x     | ✅ Supported     |
| < 1.0   | ❌ Not supported |

---

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues,
pull requests, comments, or any other public channel.** Public disclosure of
a security vulnerability before it has been addressed could put users of this
site at unnecessary risk.

Instead, please report all security vulnerabilities through the **private
contact form** on the official MrPress LLC business website, associated with
GitHub user [@HP6673](https://github.com/HP6673).

### What to Include in Your Report

To help us triage and address your report as quickly as possible, please
include as much of the following information as you are able to provide:

- **Type of vulnerability** — e.g., Cross-Site Scripting (XSS), content
  injection, open redirect, supply chain issue, dependency vulnerability,
  repository misconfiguration, etc.
- **Location** — The specific file, URL, or component where the vulnerability
  exists (e.g., `index.html`, a specific form element, a GitHub Actions
  workflow, etc.)
- **Description** — A clear, detailed description of the vulnerability and
  why it represents a security risk.
- **Impact** — Your assessment of the potential impact of the vulnerability
  if it were exploited.
- **Reproduction steps** — Step-by-step instructions that would allow
  MrPress LLC to reproduce the issue. Include any proof-of-concept code,
  screenshots, or screen recordings if applicable.
- **Suggested fix** — If you have a suggested remediation or mitigation,
  please include it. This is optional but appreciated.
- **Your contact information** — So we can follow up with you if we need
  clarification.

---

## Our Response Process

MrPress LLC is committed to handling all security reports responsibly and
transparently. Upon receiving a report, we will:

1. **Acknowledge receipt** of your report within **5 business days**.
2. **Investigate** the reported issue and assess its validity and severity.
3. **Communicate our findings** to you, including whether we have accepted
   or declined the report, and our planned timeline for remediation if
   applicable.
4. **Remediate** confirmed vulnerabilities as promptly as practicable,
   prioritizing based on severity.
5. **Notify you** when the fix has been deployed, and give you the
   opportunity to verify that the issue has been resolved to your
   satisfaction.

Response times may vary depending on the complexity of the issue and the
current workload of MrPress LLC. We appreciate your patience.

---

## Scope

The following are considered **in scope** for security reporting:

- Security issues in the `index.html` file hosted as the MrPress LLC website
- GitHub repository misconfigurations that could expose sensitive data or
  allow unauthorized access or modification
- Supply chain issues related to external resources loaded by the site
  (e.g., the Google Fonts CDN link)
- Any issue that could allow an attacker to modify the content of the live
  MrPress LLC website without authorization
- Clickjacking, content injection, or other client-side vulnerabilities
  affecting visitors to the MrPress LLC website

The following are considered **out of scope**:

- Vulnerabilities in GitHub's own platform or infrastructure (report these
  to GitHub directly at https://github.com/security)
- Vulnerabilities in Google Fonts or other third-party services that MrPress
  LLC does not control
- Social engineering attacks targeting MrPress LLC personnel
- Physical security issues
- Denial of service attacks
- Issues that require physical access to a device to exploit
- Issues in software or services not owned or operated by MrPress LLC

---

## Responsible Disclosure Policy

MrPress LLC asks that all security researchers adhere to the following
responsible disclosure principles:

- **Do not** access, modify, or delete data belonging to MrPress LLC or
  any visitor to the MrPress LLC website without explicit authorization.
- **Do not** perform actions that could degrade the availability or
  performance of the MrPress LLC website or repository.
- **Do not** disclose the vulnerability publicly until MrPress LLC has had
  a reasonable opportunity to investigate and remediate the issue.
- **Do** act in good faith and with the intent to improve the security of
  the MrPress LLC website and its visitors.

MrPress LLC commits to acting in good faith toward security researchers who
follow this policy, including not pursuing legal action against researchers
who discover and report vulnerabilities in accordance with this policy.

---

## Recognition

MrPress LLC appreciates the efforts of security researchers who responsibly
disclose vulnerabilities. While MrPress LLC does not currently operate a
formal bug bounty program, we are happy to publicly acknowledge researchers
who report valid security issues in this repository, with their permission,
once the issue has been resolved.

---

## Contact

All security-related communications must be submitted through the official
MrPress LLC contact form on the business website associated with GitHub
user [@HP6673](https://github.com/HP6673).

**Do not open a public GitHub issue for security vulnerabilities.**

---

*© 2025 MrPress LLC. All Rights Reserved.*
*This security policy is subject to change at any time without notice.*
