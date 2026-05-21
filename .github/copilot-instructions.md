# Copilot Instructions

## Repository Purpose

This is a personal learning journal tracking an AI learning journey. Content is primarily documentation and notes — not a software project with builds or tests.

## Repository Structure

- `README.md` — overview of the repo's purpose
- `claude-howto/` — notes and how-to guides for Claude CLI usage
- `.claude/skills/` — custom Claude CLI skills (Markdown files with frontmatter)
- `.claude/commands/` — custom Claude CLI slash commands

## Claude CLI Conventions

### Custom Skills
Skills live in `.claude/skills/` as Markdown files with YAML frontmatter:
```markdown
---
description: Short description shown in skill picker
---

# Skill Title
Instructions for the skill...
```

### Custom Commands
Commands live in `.claude/commands/` as Markdown files. The filename becomes the slash command (e.g., `optimize.md` → `/optimize`).

## Contributing Notes

- Notes and guides go in appropriately named subdirectories (e.g., `claude-howto/`, `openai-notes/`)
- Keep skill and command files focused and self-contained
- Update the `Last Updated` date in skill/command frontmatter when editing them
