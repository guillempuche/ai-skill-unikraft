# ai-skill-unikraft

Unikraft CLI (`unikraft`) commands for building and deploying to Unikraft Cloud. Use when working with Kraftfiles, deploying unikernels, or managing Unikraft Cloud instances/services/images. Covers the new `unikraft` CLI that replaces the legacy kraftkit `kraft`.

## Install

### Any agent

The [`skills`](https://github.com/vercel-labs/skills) CLI installs into Codex, OpenCode, Gemini CLI, Cursor, Copilot, Claude Code, and 70+ other agents:

```bash
npx skills add guillempuche/ai-skill-unikraft
```

### Claude Code

```bash
# Add marketplace (uses repo slug)
/plugin marketplace add guillempuche/ai-skill-unikraft

# Install plugin (plugin name is topic-only)
/plugin install unikraft@guillempuche-ai-skill-unikraft
```

### Gemini CLI

```bash
gemini skills install https://github.com/guillempuche/ai-skill-unikraft.git --path skills/unikraft
```

### Manual

Copy `skills/unikraft` into `.agents/skills/` (Codex, Gemini CLI, OpenCode, Mastra Code, Cursor, Copilot) or `.claude/skills/` (Claude Code).

## Part of AI Standards

This skill is also available in the [ai-standards](https://github.com/guillempuche/ai-standards) bundle with other skills and agents.

## License

MIT
