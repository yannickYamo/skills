# Skills

Practical AI skills for Claude Code — built by a product leader and full-stack builder who's spent years turning market insight into shipped products.

I'm sharing my product marketing and strategy frameworks so you can move faster from insight to execution. Each skill gives Claude the structured thinking, templates, and methodologies that took me years to refine — ready to use in seconds.

## Available Skills

| Skill | Description | Install |
|-------|-------------|---------|
| **[abx-strategy](abx-strategy/)** | Account-Based Everything (ABX) framework for complex B2B GTM — 10 frameworks, scoring models, templates | `npx skills add yannickyamo/skills/abx-strategy` |

*More skills coming soon.*

## Installation

### Option 1: CLI (recommended)

Install a single skill directly into your Claude Code environment:

```bash
npx skills add yannickyamo/skills/abx-strategy
```

### Option 2: Clone & copy

```bash
# Clone the full collection
git clone https://github.com/yannickyamo/skills.git

# Copy the skill you want into your project
cp -r skills/abx-strategy /path/to/your/project/.claude/skills/

# Or install globally for all projects
cp -r skills/abx-strategy ~/.claude/skills/
```

### Option 3: Manual download

1. Navigate to the skill folder on GitHub
2. Download `SKILL.md` and any supporting files
3. Place in `.claude/skills/` (project-level) or `~/.claude/skills/` (global)

## How Skills Work

Skills are markdown files that give Claude structured knowledge and frameworks. When installed:

- **Project-level** (`.claude/skills/`) — available in that project only
- **Global** (`~/.claude/skills/`) — available across all your projects
- Skills with a `name` in their frontmatter become `/slash-commands` in Claude Code

## Philosophy

> "Learning velocity over planning perfection"

Every skill in this collection is built from real-world application — not theory. They encode decision frameworks, scoring models, and templates that compress weeks of strategic work into structured conversations with Claude.

## License

MIT License — use freely, adapt to your context, share improvements.

## Author

**[Yannick Maurice](https://github.com/yannickyamo)** — Product leader and full-stack builder. Background in industrial technology, energy systems, and deep tech B2B.
