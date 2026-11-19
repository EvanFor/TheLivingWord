# Branch and Versioning Policy

## Branches

- `main` is the stable, reviewed project baseline.
- `dev` is the active integration branch for scripts, storyboards, visual development, prompts, and production documentation.
- Create short-lived feature branches from `dev` when a change is substantial or needs isolated review.
- Merge to `main` only after review. Do not use `main` as a scratchpad.

## Commits

Use concise, descriptive commit messages. Suggested prefixes:

- `docs:` documentation and project standards
- `story:` story structure and script changes
- `board:` storyboard and shot-list changes
- `visual:` character, location, and art-direction references
- `prompt:` generation prompt changes
- `production:` workflow, model tests, and shot tracking
- `edit:` edit, sound, and finishing notes
- `chore:` repository maintenance

## Document lifecycle

- Keep one clearly identified current working version in each active film folder.
- Preserve meaningful milestones in Git history rather than creating ambiguous files such as `final-final-v3.md`.
- Mark superseded decisions as such when their history matters.
- Do not silently overwrite an approved creative decision; record the reason for changing it.

## Generated media

Do not commit large generated video files or temporary renders directly by default. Keep prompts, metadata, shot IDs, review notes, and references in Git. Store large binaries in an agreed external location or Git LFS when the project explicitly adopts it. Never commit private credentials, API keys, or account tokens.
