# Vibe Portrait

Generate a developer personality portrait from your AI conversation history.

Install this skill in Claude Code or Codex, run it, and get:

1. **A beautiful HTML portrait page** — MBTI type, capability radar, developer rating, famous person match, and more
2. **A persona skill** — captures your thinking patterns so any AI can "think like you"
3. **A portable analysis file** — for merging data across multiple machines

## What you get

### HTML Portrait (10 visual sections)

| Section | What it shows |
|---------|---------------|
| **MBTI Type** | Four-axis personality type mapped to developer behavior |
| **Capability Radar** | Six-dimension radar chart (depth, breadth, communication, decisions, collaboration, creativity) |
| **Developer Rating** | Six-tier scale: 夯爆了 → 夯 → 人上人 → NPC → 拉 → 拉完了 |
| **Famous Match** | Which figure you're most like — from Linus Torvalds to 诸葛亮 to Marie Curie |
| **Communication Style** | Language distribution, directness score, keyword cloud |
| **Technical Domain Map** | Domain breakdown with tool/framework badges |
| **Work Rhythm** | 24-hour activity heatmap and session patterns |
| **Signature Quotes** | Your most representative messages |

### Persona Skill

A SKILL.md file installed at `~/.claude/skills/vibe-portrait-personas/me/` that captures:
- Your thinking patterns and problem-framing approach
- Your decision framework and evidence thresholds
- Your communication style and tone
- Your engineering philosophy and non-negotiables

Once generated, say **"think like me"** or **"像我一样思考"** in any conversation to activate your persona.

### Community Personas

Download other developers' persona skills and place them in `~/.claude/skills/vibe-portrait-personas/{person-id}/`. Then invoke with:

```
think like {person-id}
像{person-id}一样思考这个问题
what would {person-id} do
```

## Install

### Claude Code — Plugin Marketplace

```
/plugin marketplace add dadwadw233/vibe-portrait
/plugin install vibe-portrait@vibe-portrait
```

Then run:

```
/vibe-portrait:vibe-portrait
```

### Claude Code — Manual Skill Install

```bash
git clone https://github.com/dadwadw233/vibe-portrait.git
cp -R vibe-portrait/skills/vibe-portrait ~/.claude/skills/vibe-portrait
```

Then run:

```
/vibe-portrait
```

### Codex — Skill Install

```
$skill-installer install https://github.com/dadwadw233/vibe-portrait/tree/main/skills/vibe-portrait
```

Then:

```
Use $vibe-portrait to analyze my conversation history and generate my developer personality portrait.
```

## How it works

1. **Reads** your `~/.claude/history.jsonl` (samples ~200 messages from beginning, middle, and end)
2. **Analyzes** across 6 dimensions: communication style, technical breadth/depth, decision patterns, collaboration style, work rhythm
3. **Computes** MBTI type, developer rating, and famous person match from ~30 figures across tech, science, philosophy, and history
4. **Generates** a self-contained HTML portrait using the built-in template
5. **Creates** a persona skill at `~/.claude/skills/vibe-portrait-personas/me/`
6. **Exports** a portable JSON analysis file for multi-machine merging

## Multi-machine sync

Vibe Portrait uses a **private GitHub repo** to sync your persona across machines. No manual file copying needed.

### First time (on any machine)

```
/vibe-portrait
# → After analysis, choose "Yes — create a new repo"
# → Creates a private repo `my-vibe-portrait` on your GitHub
```

### On your other machines

```
/vibe-portrait
# → The skill detects your existing repo (from ~/.vibe-portrait-repo)
# → Pulls existing analysis data from all machines
# → Merges with local history
# → Pushes the updated portrait back
```

### What gets synced

```
my-vibe-portrait/          (private GitHub repo)
├── me/
│   └── SKILL.md           # Your persona skill (always latest merged version)
├── analysis/
│   ├── macbook-2026-04-03.json    # Analysis from your Mac
│   └── linux-4090-2026-04-03.json # Analysis from your Linux server
├── portraits/
│   └── latest.html        # Latest merged portrait
└── community/             # Downloaded persona skills from others
    └── {person-id}/
        └── SKILL.md
```

### Requirements

- `gh` CLI installed and authenticated (`gh auth login`)
- Git configured on each machine

## Privacy

- Only reads your local conversation history (`~/.claude/history.jsonl`)
- Never sends data anywhere — all analysis happens locally in your AI session
- Sensitive content (API keys, tokens, passwords) is automatically redacted
- All output files are local — you decide whether to share anything

## Rating Philosophy

Ratings follow a **materialist methodology**: judged by observable output, not by claims or intent. No flattery, no benefit of the doubt. The evidence speaks.

| Tier | Label | Description |
|------|-------|-------------|
| S+ | 夯爆了 👑 | Legendary builder — multi-domain mastery, architecture-level thinking, builds novel systems |
| S | 夯 💎 | Elite engineer — deep expertise, complex problem solver, strong tool mastery |
| A | 人上人 ⭐ | Above average — solid skills with clear growth trajectory |
| B | NPC 🤖 | Standard developer — where most developers land. Not a failure, just the statistical norm |
| C | 拉 😅 | Below average — basic tasks are challenging, heavy AI dependency |
| D | 拉完了 💀 | Not engaging — minimal technical interaction |

Every tier includes strengths AND growth areas. The goal is accurate self-knowledge, not ego validation.

## Persona Directory Layout

```
~/.claude/skills/vibe-portrait-personas/
├── me/                  # Your own persona (auto-generated)
│   └── SKILL.md
├── linus-torvalds/      # Downloaded community persona
│   └── SKILL.md
└── zhuge-liang/         # Downloaded community persona
    └── SKILL.md
```

## Requirements

- Claude Code or Codex with conversation history
- At least 20 messages in history for a meaningful portrait
- A modern browser to view the generated HTML

## License

MIT
