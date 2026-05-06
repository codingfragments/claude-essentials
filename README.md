# Codingfragments Essentials

A Claude Code plugin: a toolkit of skills and methods for designing and planning documents and projects with Claude.

## Status

Scaffold only — no skills, agents, or hooks yet. Components will be added incrementally.

## Layout

```
.claude-plugin/plugin.json   # plugin manifest
```

Planned (added on demand as components are introduced):

- `skills/<skill-name>/SKILL.md` — one directory per skill
- `agents/<agent-name>.md` — autonomous agents
- `hooks/hooks.json` — event-driven automation

## Local installation

From this directory:

```sh
claude --plugin-dir /Users/stefan.marx/vlab/tools/claude-plugin
```

Or symlink/copy into a Claude Code marketplace once published.

## Author

Stefan Marx — stefan@marx-merten.de
