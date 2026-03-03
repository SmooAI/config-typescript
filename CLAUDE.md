# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

**Use Context7 MCP server for up-to-date library documentation.**

## Project Overview

`@smooai/config-typescript` is a collection of TypeScript configuration presets used across all SmooAI projects. It provides standardized `tsconfig` settings for different project types.

### Config Presets

- `base.json` -- Base TypeScript config (all projects extend this)
- `nextjs.json` -- Next.js projects
- `react-app.json` -- React applications
- `react-library.json` -- React component libraries
- `vite.json` -- Vite projects

---

## Git Workflow -- Worktrees

All feature work MUST happen in git worktrees. The main worktree at `~/dev/smooai/config-typescript/` must ALWAYS stay on the `main` branch.

### Creating a worktree

```bash
cd ~/dev/smooai/config-typescript
git worktree add ../config-typescript-SMOODEV-XX-short-desc -b SMOODEV-XX-short-desc main
cd ../config-typescript-SMOODEV-XX-short-desc
pnpm install
```

### Branch naming

```
SMOODEV-XX-short-description
```

### Commit messages

Always prefix with the Jira ticket. Explain **why**, not just what:

```
SMOODEV-XX: Add survey validation to prevent duplicate submissions
```

### Merging to main

```bash
cd ~/dev/smooai/config-typescript
git checkout main && git pull --rebase
git merge SMOODEV-XX-short-desc --no-ff
git push
```

### Cleanup after merge

```bash
git worktree remove ~/dev/smooai/config-typescript-SMOODEV-XX-short-desc
git branch -d SMOODEV-XX-short-desc
```

---

## Commands

```bash
pnpm install          # Install dependencies
pnpm format           # Format with Prettier
```

This is a minimal config-only package -- there is no build, test, or lint step. Changes are JSON config files.

---

## Changesets & Versioning

Always add changesets when the package changes:

```bash
pnpm changeset        # Interactive changeset creation
```

Release is automated via GitHub Actions.

---

## CI / GitHub Actions

PR checks run on every PR to `main`. CI must be green before merging.

```bash
gh run list                          # List recent workflow runs
gh run view <run-id> --log-failed    # View failed step logs
```
