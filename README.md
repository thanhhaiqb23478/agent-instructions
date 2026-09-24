# agent-instructions

CLAUDE.md templates + cursor rules that actually help

## Usage

```bash
# Claude Code reads CLAUDE.md from the repo root automatically
```

## Highlights

- Kept short: agents read every token every time
- Per-archetype CLAUDE.md templates (api / cli / lib)
- Global coding-style rules in rules/
- Review checklist baked into instructions

## Install

```bash
# pick a template
cp templates/CLAUDE.api.md your-project/CLAUDE.md
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── rules/
│   ├── review.md
│   └── style.md
├── templates/
│   ├── CLAUDE.api.md
│   └── CLAUDE.cli.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
└── SECURITY.md
```
