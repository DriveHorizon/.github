# Security policy

## Report a vulnerability

Report a vulnerability in the app or in the website privately, through the
[private security advisory](https://github.com/DriveHorizon/.github/security/advisories/new)
of the `.github` repository. Only the maintainers can read it. Never describe an exploitable problem
in a public issue.

Include the following.

- The problem and what an attacker can do with it.
- The steps that reproduce it.
- The version of Drive Horizon, or the address of the page on the
  website.

## Scope

- **The app.** Drive Horizon runs on Windows. It connects to the network
  to check for updates and to show multiplayer traffic. Its truck screen
  plugin loads into the game process. Its parsers read the game's
  telemetry and map files.
- **The website.** The public pages and the server that renders them.

## Supported versions

The app supports its latest release. The website supports what is
deployed from `main`.
