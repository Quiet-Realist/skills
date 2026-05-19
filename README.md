# Quiet Realist Skills

A collection of agent skills for AI coding agents. Skills follow the [Agent Skills](https://agentskills.io/) format and work with 40+ agents including Claude Code, Cursor, Windsurf, Codex, and more.

## Install

Install all skills using the [`skills`](https://github.com/vercel-labs/skills) CLI:

```bash
npx skills@latest add quiet-realist/skills
```

Install a specific skill:

```bash
npx skills@latest add quiet-realist/skills --skill character-distiller
```

## Available Skills

### character-distiller

Turns character material into structured Character Templates usable as both human writing references and AI prose refinement lenses. Supports three modes: fresh build from Q&A interviews, augmenting an existing template with new sessions, and extracting character sketches from a full manuscript.

**Category:** Writing

**Use when:**
- Conducting character interviews and want structured output
- Augmenting an existing character template with new material
- Extracting character profiles from a manuscript
- Any character development work across sessions

[View skill details](./character-distiller/)

### instagram-saves-catalog

Ingests posts from one or more Instagram saved-collection URLs into a local, searchable catalog of Markdown files. Runs in your own logged-in browser via the [Claude in Chrome](https://claude.ai/chrome) extension — no third-party API, no headless scraping. Incremental: a URL registry tracks every post already ingested so re-runs only fetch new ones. The per-post analysis is pluggable via a template file, so the same skill can produce writing seeds, research notes, marketing breakdowns, and more.

**Category:** Research

**Use when:**
- Building a local catalog from your Instagram saved collections
- Refreshing an existing catalog with newly saved posts
- Producing per-post analysis cards (writing seeds, research notes, marketing intelligence) from a custom template
- Recovering a lost or corrupted catalog registry from existing files

[View skill details](./instagram-saves-catalog/)

## License

MIT
