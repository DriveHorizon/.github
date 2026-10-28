# Agent instructions

This repository holds what every Drive Horizon repository shares: the
organization profile, the pull request and issue templates, the Renovate
rules, the security policy and the code of conduct. A change here reaches
`drive-horizon` and `website` at once.

| Folder in the workspace | Repository | Content |
|---|---|---|
| `drive-horizon/` | `DriveHorizon/drive-horizon` | The Windows app |
| `website/` | `DriveHorizon/website` | The website |
| `.github/` | `DriveHorizon/.github` | This repository |

- Before you change a repository, read its `AGENTS.md` and
  `CONTRIBUTING.md`. This repository follows those of `drive-horizon` for
  the order of work, branches, commits and pull requests.
- For a change across repositories, open one pull request per repository
  and link them. Merge the app first: the website states only what is on
  `main` of the app.
- Keep the pull request template in line with the "Branches and pull requests"
  section of both `CONTRIBUTING.md` files, and change that section in
  both repositories together.
- Keep `profile/README.md` to what the app is, the repositories and the
  security policy.
- Only `validate.yml` runs here, on `renovate-config.json`. Check links
  and the commit subject by hand.
- Merge a pull request here only when the owner asks in the conversation.
- Write in English.
