# Security Policy

## Reporting Vulnerabilities

If you discover a security vulnerability in any civic-source project, please report it responsibly.

**Do NOT open a public GitHub issue for security vulnerabilities.**

Instead, use [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) to report the vulnerability privately. Navigate to the affected repository's Security tab and click "Report a vulnerability."

## What We Consider Security Issues

- XML entity expansion (XXE) in document parsing
- Path traversal in file generation
- Credential or secret exposure
- Dependency vulnerabilities with known exploits
- CI/CD pipeline injection vectors

## Response Timeline

We aim to acknowledge security reports within 48 hours and provide a fix or mitigation plan within 7 days for critical issues.
