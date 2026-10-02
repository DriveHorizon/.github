# Agent instructions

This repository holds the files that every Drive Horizon repository
shares. A change here reaches `drive-horizon` and `website` at once. This
file also says how the three repositories sit together in a workspace.

## The repositories

| Folder | GitHub repository | Content |
|---|---|---|
| `drive-horizon/` | `DriveHorizon/drive-horizon` | The Windows app |
| `website/` | `DriveHorizon/website` | The website |
| `.github/` | `DriveHorizon/.github` | The organization profile and the files that all repositories share: the Renovate rules, the pull request template, the issue templates, the security policy and the code of conduct |

In the workspace of the maintainers, the three folders sit side by side in
one folder that is not a repository.

## Before you change a file

1. Read the `AGENTS.md` and the `CONTRIBUTING.md` of the repository that
   holds the file. Follow them for the whole task.
2. Read every other `AGENTS.md` on the path from the repository root to
   the file.
3. If the task touches several repositories, read the rules of each one
   before the first change. The rules differ.

This repository has no `CONTRIBUTING.md` of its own. Follow
`drive-horizon/CONTRIBUTING.md` for branches, commits and pull requests,
and `drive-horizon/AGENTS.md` for the order of work.

## Change several repositories

1. Work in each repository on its own branch. Open one pull request per
   repository.
2. Link each pull request from the other.
3. Merge the pull request of `drive-horizon` first. The website states
   only what is on `main` of the app. If the website pull request states
   something that is not on `main` yet, keep it a draft until the app pull
   request is merged.

A worktree that a rule asks for sits next to its repository, in the
workspace. Remove it after the merge.

## Change this repository

- Before you change the pull request template, the issue templates or
  `renovate-config.json`, read the `CONTRIBUTING.md` of both
  repositories. Keep the template in line with their "Write the
  description" section.
- The sections "Branches and pull requests" and "Commit messages" of
  `CONTRIBUTING.md` exist in both repositories, because an agent reads the
  files of its own clone. When you change one copy, change the other in
  the same task.
- Take every fact about the app in `profile/README.md` from the
  `README.md` on `origin/main` of `drive-horizon`.
- Never edit `CODE_OF_CONDUCT.md`. It is the Contributor Covenant text.
- Write documents and commits in English. Write to the user in their
  language.
- A change here reaches both repositories, so merge a pull request only
  when the user asks you to in the current conversation.
