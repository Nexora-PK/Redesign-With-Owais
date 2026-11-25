# Claude Code Integration Guide - Redesign With Owais

To integrate the Redesign With Owais design system with Claude Code:

### Option 1: Global Setup
```bash
git clone https://github.com/Nexora-PK/Redesign-With-Owais.git ~/.claude/plugins/redesign-with-owais
```

### Option 2: Project Skill
Copy `skills/redesign-with-owais/SKILL.md` into your project's `.claude/skills/redesign-with-owais/SKILL.md`.

### Option 3: Add to CLAUDE.md
Add the following instruction to your project's `CLAUDE.md`:
```markdown
## Frontend UI/UX Design System (Redesign With Owais)
For all frontend development, React, Tailwind, HTML, and CSS styling tasks:
- Automatically apply the Redesign With Owais framework from `skills/redesign-with-owais/SKILL.md`.
- Eliminate AI tells: No purple gradients, glowing blur blobs, emoji badges, or micro-caps tracking.
- Enforce quiet chrome with focused richness in 1-2 focal content moments.
- Redesign systematically: Spacing -> Copy -> Typography -> Color -> Details.
```
