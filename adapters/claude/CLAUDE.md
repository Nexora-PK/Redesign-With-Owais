# Claude Code Integration Guide

To use the Nexify Redesign skill with Claude Code:

### Option 1: Global Setup
```bash
git clone https://github.com/Nexora-PK/Nexify-Redesign.git ~/.claude/plugins/nexify-redesign
```

### Option 2: Project Skill
Copy `skills/nexify-redesign/SKILL.md` to `.claude/skills/nexify-redesign/SKILL.md`.

### Option 3: Append to CLAUDE.md
Add this to your `CLAUDE.md`:
```markdown
## Frontend Design & Unslopping (Nexify Redesign)
For all frontend, React, Tailwind, HTML, and CSS design tasks:
- Automatically apply the Nexify Redesign methodology in `skills/nexify-redesign/SKILL.md`.
- Eliminate AI-slop tells (no purple gradients, glowing blobs, emoji badges, or uppercase tracked labels).
- Enforce quiet chrome and execute in order: Spacing -> Copy -> Type -> Color -> Details.
```
