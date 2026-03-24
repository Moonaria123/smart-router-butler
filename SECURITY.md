# Security Policy

## Supported versions

| Scope | Policy |
|-------|--------|
| **Security fixes** | Preferably applied to the latest commit on `main`. Maintainers may backport fixes to the most recent release tag depending on severity and capacity. |
| **Unsupported** | Archived versions and branches not documented in this repository; use at your own risk. |

## Reporting a vulnerability (responsible disclosure)

If you discover a **security vulnerability** (e.g. unauthorized access, exposure of key material, remote code execution, authentication bypass), **do not** disclose exploitable details in public Issues, Discussions, or social media.

### Preferred channels

1. **GitHub private vulnerability reporting** (recommended): **Security → Report a vulnerability** on this repository (must be enabled for the repo).
2. **Email**: If maintainers list a security contact email in the README or at the bottom of this file, send mail with the subject prefix `[SECURITY]`.
3. **Direct message to maintainers**: Only if verifiable contact information is published on GitHub.

### What to include

- Affected versions, commits, or tags (if known)
- Steps to reproduce and a minimal proof of concept (PoC) when appropriate
- Potential impact and affected components
- Whether the issue is known to be exploited in the wild (if you can say so safely)

### What to expect

Maintainers will try to acknowledge reports in a reasonable timeframe. **No specific SLA is guaranteed.** Critical fixes may be published via **GitHub Security Advisories** and **Releases**.

### Coordinated disclosure

Please avoid public disclosure of vulnerability details until a fix is available or maintainers explicitly agree, so users have time to upgrade.

## Non-security issues

Use **[Issues](https://github.com/Moonaria123/smart-router-butler/issues)** (not the security channel) for:

- Configuration questions, feature requests, and general bugs that are not security-sensitive
- Known CVEs in dependencies (you may open a PR to bump dependencies)

## Security contact

If a dedicated security email is published in the repository **README** or in organization documentation, use it with the `[SECURITY]` subject prefix. Otherwise, use **GitHub private vulnerability reporting** (above).
