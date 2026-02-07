# Skills

Practical AI skills for Claude Code, built by a product leader and full-stack builder who's spent years turning market insight into shipped products.

I'm sharing my product marketing and strategy frameworks so you can move faster from insight to execution. Each skill gives Claude the structured thinking, templates, and methodologies that took me years to refine. Ready to use in seconds.

## Available Skills

### GTM & Marketing

| Skill | Description | Install |
|-------|-------------|---------|
| **[abx-strategy](abx-strategy/)** | Account-Based Everything (ABX) framework for complex B2B GTM — 10 frameworks, scoring models, templates | `npx skills add yannickyamo/skills/abx-strategy` |

### Modern Product Operating Model

| Skill | Description | Install |
|-------|-------------|---------|
| **[product-operating-model](product-operating-model/)** | Meta-skill index — overview of all 6 product skills and how they connect | `npx skills add yannickyamo/skills/product-operating-model` |
| **[product-strategy](product-strategy/)** | Strategy System — ICP, positioning, pricing, GTM motion, strategic bets, 1-page canvas | `npx skills add yannickyamo/skills/product-strategy` |
| **[product-discovery](product-discovery/)** | Discovery System — continuous discovery, interview snapshots, OST, assumption testing | `npx skills add yannickyamo/skills/product-discovery` |
| **[product-architecture](product-architecture/)** | Product System — capability blocks, bet backlog, roadmap, solution briefs | `npx skills add yannickyamo/skills/product-architecture` |
| **[product-delivery](product-delivery/)** | Delivery System — staged rollout, metrics hierarchy, launch checklist, bet retrospectives | `npx skills add yannickyamo/skills/product-delivery` |
| **[ai-native-product](ai-native-product/)** | AI-Native overlay — agency assessment, calibration plans, eval strategy | `npx skills add yannickyamo/skills/ai-native-product` |
| **[product-leadership](product-leadership/)** | Leadership overlay — portfolio review, board metrics, operating rhythm, PM development | `npx skills add yannickyamo/skills/product-leadership` |

## Installation

### Option 1: CLI (recommended)

Install a single skill directly into your Claude Code environment:

```bash
npx skills add yannickyamo/skills/product-strategy
```

Or install the complete Product Operating Model collection:

```bash
npx skills add yannickyamo/skills/product-operating-model
npx skills add yannickyamo/skills/product-strategy
npx skills add yannickyamo/skills/product-discovery
npx skills add yannickyamo/skills/product-architecture
npx skills add yannickyamo/skills/product-delivery
npx skills add yannickyamo/skills/ai-native-product
npx skills add yannickyamo/skills/product-leadership
```

### Option 2: Clone & copy

```bash
# Clone the full collection
git clone https://github.com/yannickyamo/skills.git

# Copy the skill you want into your project
cp -r skills/product-strategy /path/to/your/project/.claude/skills/

# Or install globally for all projects
cp -r skills/product-strategy ~/.claude/skills/
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
