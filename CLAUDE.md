# CLAUDE.md — GitHub Profile Repo

## Project Overview

This is the `segurudigital/.github` organization profile repository. It controls the public-facing README shown on the [Seguru Digital GitHub org page](https://github.com/segurudigital).

## Repo Structure

```
profile/
  README.md      # Org profile README (displayed on GitHub)
CLAUDE.md        # Agent context (this file)
TASKS.md         # Current tasks and status
CHANGELOG.md     # Change log
.gitignore       # System file exclusions
```

## Key Rules

- **Single content file:** `profile/README.md` is the only published content. All profile changes go here.
- **Tone:** Professional, clear, mission-driven. No hype. Matches Seguru Digital brand voice.
- **Formatting:** GitHub-flavored Markdown only. Must render correctly on GitHub's org profile page.
- **No sensitive data:** No internal URLs, credentials, pricing details, or client names.
- **Keep it concise:** This is a landing page, not a docs site.

## Git Workflow

- Branch: `main` (direct push OK for this repo)
- Commit format: conventional commits (`docs:`, `chore:`, `feat:`)
- Tag releases when making significant content updates

## Owners

- Samuel Clarke (samuel@seguru.digital)
- Cameron Gilroy
