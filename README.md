# Website-skills

Vercel agent skills for building high-quality websites — collected from the official Vercel skills directory and skills.sh.

## Skills

| Skill | What it does |
|---|---|
| `web-design-guidelines` | Review UI code against Vercel's Web Interface Guidelines: accessibility, focus states, forms, animation, typography, performance, dark mode, i18n, and anti-patterns. Outputs `file:line` findings. |
| `vercel-react-best-practices` | Vercel Engineering's 70 performance rules across 8 categories (waterfalls, bundle size, server-side, re-renders, rendering, JS, advanced) with per-rule code examples in `rules/`. |
| `vercel-composition-patterns` | React composition patterns that scale — avoids boolean prop proliferation. |
| `vercel-react-view-transitions` | React view transitions for smooth, performant page transitions. |

## Installing into Hermes

### Option A — one-shot (recommended for this repo)

```
/learn https://github.com/vaferkhanom/Website-skills
```

Hermes reads the repo and installs every skill it finds.

### Option B — register as a persistent source (tap)

```bash
hermes skills tap add vaferkhanom/Website-skills
hermes skills install vaferkhanom/Website-skills/web-design-guidelines
hermes skills update
```

### Option C — CLI install (other agents)

```bash
npx skills add vaferkhanom/Website-skills
```

## Layout

One folder per skill, each with `SKILL.md` (+ optional `rules/`, `references/`):

```
Website-skills/
├── web-design-guidelines/SKILL.md
├── vercel-react-best-practices/SKILL.md
│   └── rules/*.md
├── vercel-composition-patterns/SKILL.md
├── vercel-react-view-transitions/SKILL.md
└── README.md
```

Sources: [vercel.com/docs/agent-resources/skills](https://vercel.com/docs/agent-resources/skills), [skills.sh](https://skills.sh) — all skills © Vercel (MIT).
