# Security Policy

The security of this project is taken seriously. We appreciate your efforts to
responsibly disclose any findings and will make every effort to acknowledge
your contributions.

## Supported Versions

Security updates are provided only for the latest released version of this
app. Users are strongly encouraged to keep their installations up to date.

| Version        | Supported          |
| -------------- | ------------------ |
| Latest release | :white_check_mark: |
| Older releases | :x:                |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues,
discussions, or pull requests.**

Instead, report them privately through GitHub's private vulnerability
reporting:

[**Report a vulnerability**](https://github.com/hassio-addons/app-grafana/security/advisories/new)

If for any reason you are unable to use GitHub's private vulnerability
reporting, you may also reach out to the maintainer by email at
[opensource@frenck.dev](mailto:opensource@frenck.dev).

When reporting, please include as much of the following as possible:

- A clear description of the vulnerability and its potential impact.
- Steps to reproduce, or a proof of concept.
- Affected version(s) of the app.
- Any known mitigations or workarounds.

## Disclosure Timeline

- **Acknowledgement:** you will receive an acknowledgement of your report
  within **48 hours**.
- **Initial assessment:** a triage and initial severity assessment will be
  shared within **7 days** of the acknowledgement.
- **Fix and disclosure:** valid reports are targeted for resolution and
  coordinated public disclosure within **90 days** of the initial report,
  depending on complexity and impact.

You will be kept informed throughout the process and credited in the release
notes for the fix, unless you prefer to remain anonymous.

## Out of Scope

The following are **not** considered security vulnerabilities in this project:

- Vulnerabilities in upstream or transitive dependencies. These are handled
  continuously by [Renovate](https://github.com/renovatebot/renovate) and
  addressed through regular dependency updates.
- Issues in Grafana itself; please report those directly to the
  [Grafana project](https://github.com/grafana/grafana/security/policy).
- Issues in the Home Assistant Supervisor or Operating System; please report
  those directly to the
  [Home Assistant project](https://github.com/home-assistant/core/security/policy).
- Exposure of the app to untrusted networks as a result of the user's own
  configuration, such as publishing the direct port without SSL.

## Scope

This security policy covers the Grafana Home Assistant app published from this
repository, including its container images and configuration.
