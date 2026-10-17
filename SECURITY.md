# Security policy

## Scope

This repository contains no application code. It is a profile README, two static
SVG banners, and two small GitHub Actions workflows. The realistic security
concerns here are narrow:

- a link or image that points somewhere malicious,
- a workflow that runs with more permission than it needs,
- a secret accidentally committed.

## Reporting a problem

Please **don't** open a public issue for a security problem.

- Preferred: use GitHub's private vulnerability reporting — go to the **Security**
  tab of this repository and choose **Report a vulnerability**.
- Alternative: send me a DM on X at [@Aayush9139](https://x.com/Aayush9139).

Include what you found, where, and what an attacker could do with it. I'll confirm
receipt as soon as I can and follow up with a fix or an explanation.

## How this repo is kept safe

- **No secrets.** Nothing in this repository requires a key, token, or password.
- **Minimal workflow permissions.** `.github/workflows/snake.yml` declares
  `contents: write` and uses only the automatic `GITHUB_TOKEN` to publish to a
  generated `output` branch. `.github/workflows/greetings.yml` declares
  `issues: write` and `pull-requests: write` to welcome first-time contributors,
  and never checks out or executes repository code.
- **No third-party pipes.** Workflows use pinned, well-known actions and no
  untrusted input is passed into a shell.
