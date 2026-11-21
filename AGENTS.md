# Agent instructions

This repository holds what every Drive Horizon repository shares: the organization profile, the pull request and issue
templates, the Renovate preset, the security policy and the code of conduct. A change here reaches `drive-horizon` and
`website` at once.

- Ship a change as `../drive-horizon/CONTRIBUTING.md` says, but merge it only when the owner asks.
- For a change across repositories, open one pull request per repository, link them, and merge the app first. The
  website states only what is on `main` of the app.
- Change `pull_request_template.md` and the "Ship a change" section of both `CONTRIBUTING.md` files together.
- Keep `profile/README.md` to what the app is, the repositories and the security policy.
- `validate.yml` checks `renovate-config.json`. Check the links and the title by hand.
- Write in English.
