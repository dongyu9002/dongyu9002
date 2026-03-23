# CLAUDE.md

This file provides guidance for AI assistants (Claude and others) working with this repository.

## Repository Overview

This is a **GitHub profile repository** (`dongyu9002/dongyu9002`). It is a special GitHub repository whose `README.md` is automatically displayed on the owner's public GitHub profile page at [github.com/dongyu9002](https://github.com/dongyu9002).

## Repository Structure

```
dongyu9002/dongyu9002
├── README.md    # GitHub profile page content (displayed publicly)
└── CLAUDE.md    # This file — guidance for AI assistants
```

## Purpose & Conventions

### README.md
- This is the **profile README** — it renders directly on the GitHub profile page.
- It should be written in GitHub-flavored Markdown.
- Changes here are immediately visible to anyone visiting the profile.
- Keep content professional, accurate, and up to date.
- Common sections include: bio, interests, skills, current projects, contact info, and GitHub stats.

### Editing Guidelines
- **Do not** add unnecessary files or directories — this repo serves a single, focused purpose.
- **Do not** commit secrets, credentials, or private information.
- Any images or badges referenced in README.md should use stable, publicly accessible URLs.
- Prefer concise, readable Markdown over complex HTML within the README.

## Development Workflow

1. **Branch**: Make changes on a feature branch (e.g., `update-profile`, `add-stats-badge`).
2. **Commit**: Write clear commit messages describing what changed and why.
3. **Push**: Push the branch to `origin`.
4. **PR**: Open a pull request targeting `main` for review before merging.
5. **Merge**: Merge into `main` — the profile page updates automatically.

## Key Notes for AI Assistants

- The only user-facing file is `README.md`. Treat changes to it with care — they are public.
- There is no build system, test suite, CI pipeline, or package manager in this repository.
- No code execution is expected or required.
- When asked to update the profile, edit `README.md` directly.
- When asked to add documentation or AI guidance, edit this `CLAUDE.md` file.
- Branch naming convention in use: `claude/<task-description>-<id>` for AI-generated branches.
