# Security Policy

Lilloweb renders untrusted web content in Chromium and lets local AI agents
control the browser over a local connection. We take security reports seriously.

## Reporting a vulnerability

**Please do not open a public issue for a security problem.**

Email **lillodominador@gmail.com** with the subject "Lilloweb security report".

Please include:

- What an attacker gains, and what they need to start (a visited page? a
  process on the same machine? an agent the person already trusts?)
- Your Lilloweb version (**Settings → About**) and your Windows version
- Steps to reproduce, ideally a minimal page or script

You can expect an acknowledgement within 5 working days. Credit is given in the
release notes when a fix ships, unless you ask otherwise.

## Supported versions

Lilloweb is pre-1.0. Only the latest release gets fixes.

## Out of scope

- Vulnerabilities in Chromium itself; please report those to the
  [Chromium project](https://issues.chromium.org/).
- Findings that need the attacker to already run code as the user, or to have
  physical access to an unlocked computer.
