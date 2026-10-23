# Security Policy

Lumen processes sensitive personal data on-device, including camera and
microphone input, location, and medical information. We take security
reports seriously and ask that you report vulnerabilities responsibly.

## Reporting a vulnerability

Do not open a public GitHub issue for a security vulnerability. Instead,
use GitHub's private vulnerability reporting on the affected repository
(repository page, "Security" tab, "Report a vulnerability"), which opens
a private advisory visible only to maintainers.

Include, as far as you are able to:

- A description of the vulnerability and its potential impact.
- Steps to reproduce it, including the affected repository, commit, and
  platform (Android, iOS, server).
- Any proof-of-concept code, logs, or screenshots, redacted of personal
  data.

## Response

Maintainers aim to acknowledge a new report within 5 business days and
to provide an initial assessment within 14 days. Fix timelines depend on
severity and complexity; we will keep the reporter informed throughout.

## Supported versions

Only the latest tagged release of each repository receives security
fixes until the project reaches a stable 1.0 across the organization.

## Scope

In scope: any code in the `lumen-assistive` organization. Out of scope:
third-party services the project links to but does not operate, and
social engineering against individual contributors.
