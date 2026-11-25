# Claude Code Integration Guide - Nexify Redesign

To integrate the Nexify Redesign design system with Claude Code:

### Option 1: Global Setup
```bash
git clone https://github.com/Nexora-PK/Nexify-Redesign.git ~/.claude/plugins/nexify-redesign
```

### Option 2: Project Skill
Copy `skills/nexify-redesign/SKILL.md` into your project's `.claude/skills/nexify-redesign/SKILL.md`.

### Option 3: Add to CLAUDE.md
Add the following instruction to your project's `CLAUDE.md`:
```markdown
## Frontend UI/UX Design System (Nexify Redesign)
For all frontend development, React, Tailwind, HTML, and CSS styling tasks:
- Automatically apply the Nexify Redesign framework from `skills/nexify-redesign/SKILL.md`.
- Eliminate AI tells: No purple gradients, glowing blur blobs, emoji badges, or micro-caps tracking.
- Enforce quiet chrome with focused richness in 1-2 focal content moments.
- Redesign systematically: Spacing -> Copy -> Typography -> Color -> Details.
```
