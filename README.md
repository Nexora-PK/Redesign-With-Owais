# Nexify Redesign - Enterprise UI/UX Engineering System

[![License: Proprietary](https://img.shields.io/badge/License-Proprietary%20|%20All%20Rights%20Reserved-red.svg)](LICENSE)
[![Usage](https://img.shields.io/badge/Usage-Free%20to%20Install%20&%20Use-brightgreen.svg)](#license--ownership)
[![AI Compatibility](https://img.shields.io/badge/AI%20Tools-Antigravity%20|%20Claude%20|%20Cursor%20|%20ChatGPT-blue.svg)](#installation--setup)

A high-performance design engineering plugin and skill system designed to transform AI-generated ("vibecoded") web prototypes into polished, human-crafted interfaces with distinctive character. Built for **Google Antigravity**, **Claude Desktop**, **Claude Code**, **Cursor**, **ChatGPT**, and modern frontend development workflows.

---

## ⚡ What Nexify Redesign Does

- **Eliminates AI Tells:** Systematically removes purple gradient headlines, ambient glowing blur blobs, emoji badges, bloated cards, and micro-caps tracking.
- **Enforces Quiet Chrome:** Keeps backgrounds, sidebars, cards, and buttons neutral and calm (tinted zincs/lights + 1 primary accent).
- **Injects Focused Richness:** Directs visual attention to 1–2 intentional focal moments (interactive product previews, SVG charts, or high-contrast tables).
- **Strict 5-Pass Refactoring Order:**
  1. *Spacing & Rhythm* (strict 8pt mathematical grid)
  2. *Copy & Voice* (clear, short value propositions in natural sentence case)
  3. *Typography* (dual-typeface pairing, generous line-heights)
  4. *Color & Contrast* (90% quiet neutrals, 10% functional accent, WCAG AAA contrast)
  5. *Precision Details* (subtle 1px alpha borders, multi-layer shadows, balanced corner radii)

---

## 📂 Repository Structure

```text
Nexify-Redesign/
├── plugin.json                              # Universal plugin manifest
├── README.md                                # Setup & usage documentation
├── LICENSE                                  # Proprietary license terms
├── .claude-plugin/                          # Claude Desktop integration
│   ├── plugin.json
│   └── marketplace.json
├── skills/
│   └── nexify-redesign/
│       ├── SKILL.md                         # Main skill with YAML frontmatter
│       ├── references/                      # Heuristics, tokens, RTL, visual patterns
│       └── scripts/                         # UI capture & audit scripts
├── rules/
│   └── AGENTS.md                            # Always-on baseline frontend rules
└── adapters/
    ├── cursor/
    │   └── nexify-redesign.mdc              # Cursor IDE rule (.cursor/rules/)
    ├── claude/
    │   └── CLAUDE.md                        # Claude Code configuration guide
    └── system-prompts/
        └── nexify-redesign-prompt.txt       # System prompt for ChatGPT / Claude Web
```

---

## 🚀 Installation & Setup

### 1. Google Antigravity & Gemini CLI

#### Global Installation (All Workspaces):
```powershell
git clone https://github.com/Nexora-PK/Nexify-Redesign.git "$HOME\.gemini\config\plugins\nexify-redesign"
```

#### Project-Specific Installation:
```bash
mkdir -p .agents/plugins
git clone https://github.com/Nexora-PK/Nexify-Redesign.git .agents/plugins/nexify-redesign
```

---

### 2. Claude Desktop App
1. Download `Nexify-Redesign.zip`.
2. In **Claude Desktop**, open **Plugins** from the left sidebar.
3. Click **Add ▾** ➔ **Upload plugin**.
4. Select `Nexify-Redesign.zip` and click **Upload**.

---

### 3. Claude Code CLI
```powershell
New-Item -ItemType Directory -Force -Path "$HOME\.claude\skills\nexify-redesign"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/Nexora-PK/Nexify-Redesign/main/skills/nexify-redesign/SKILL.md" -OutFile "$HOME\.claude\skills\nexify-redesign\SKILL.md"
```

---

### 4. Cursor IDE
Copy the `.mdc` rule into your project's `.cursor/rules/` directory:
```bash
mkdir -p .cursor/rules
cp adapters/cursor/nexify-redesign.mdc .cursor/rules/nexify-redesign.mdc
```

---

### 5. ChatGPT / Custom GPTs / Claude.ai Projects
* **Custom GPTs:** Upload `skills/nexify-redesign/SKILL.md` to **Knowledge** and paste `adapters/system-prompts/nexify-redesign-prompt.txt` into **Instructions**.
* **Claude Projects:** Upload `SKILL.md` to Project Knowledge.

---

## 💡 Suggested Starter Prompts

- *"Redesign and elevate this frontend screen with Nexify Redesign."*
- *"Audit this UI for AI tells and refactor spacing, typography, and color architecture."*
- *"Convert this prototype into a production-grade, human-crafted SaaS screen."*

---

## 📄 License & Ownership

**Copyright © 2026 Nexora PK / Owais Kayani. All Rights Reserved.**
- Free to clone, download, install, and execute for personal and commercial development.
- Unauthorized re-hosting, mirroring, or distribution under another name is strictly prohibited.
