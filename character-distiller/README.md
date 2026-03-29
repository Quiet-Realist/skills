# character-distiller

> Distill character profiles from source material

**Category:** Writing

## Install

Install using the [`skills`](https://github.com/vercel-labs/skills) CLI:

```bash
npx skills@latest add quiet-realist/skills --skill character-distiller
```

Install all skills from this repository:

```bash
npx skills@latest add quiet-realist/skills
```

### Manual Installation

<details>
<summary>Devin / Windsurf</summary>

```bash
# Project-level
cp -r character-distiller .cognition/skills/character-distiller
# or
cp -r character-distiller .windsurf/skills/character-distiller

# Global
cp -r character-distiller ~/.config/cognition/skills/character-distiller
```

</details>

<details>
<summary>Claude Code</summary>

```bash
# Project-level
cp -r character-distiller .claude/skills/character-distiller

# Global
cp -r character-distiller ~/.claude/skills/character-distiller
```

</details>

<details>
<summary>Cursor</summary>

```bash
# Project-level
cp -r character-distiller .cursor/skills/character-distiller
```

</details>

<details>
<summary>Codex</summary>

```bash
# Copy SKILL.md content into your codex instructions
cat character-distiller/SKILL.md >> AGENTS.md
```

</details>

<details>
<summary>Gemini CLI</summary>

```bash
# Copy SKILL.md content into your Gemini instructions
cat character-distiller/SKILL.md >> GEMINI.md
```

</details>

## Usage

Once installed, invoke in your agent session:

```
/character-distiller
```

## License

MIT
