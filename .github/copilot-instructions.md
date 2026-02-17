# GitHub Copilot Instructions – My-Ruby

This repository uses GitHub Copilot for PR reviews.

## Dependabot gem upgrade PRs

When reviewing PRs created by Dependabot that bump Ruby gems
(changes in `Gemfile` / `Gemfile.lock`):

- Apply the rules in
  `.github/instructions/gem-upgrades.instructions.md`.
- Detect Dependabot PRs by author (`dependabot[bot]`) or branch name
  starting with `dependabot/`.
- Prefer **one structured summary comment** (overview, gem changes,
  risk level, CI status) over many noisy inline comments.