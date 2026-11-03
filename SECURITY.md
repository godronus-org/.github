# Security policy

This policy covers every repository in `godronus-org` that doesn't carry its own
`SECURITY.md`.

## Reporting a vulnerability

Don't open a public issue, PR or discussion.

Report it privately: open the affected repository, go to **Security → Report a vulnerability**, and fill in the form.
Only the maintainers see the report.

Include the affected repo and version (tag or commit), what an attacker can do,
and the steps to reproduce it.

## How we fix it

Every fix is developed in a **GitHub private security advisory**, which uses a
temporary private fork. The flaw stays private until the patched release ships.
After that we publish the advisory, and a CVE if one applies.

Supported version: the latest release of each repository.
