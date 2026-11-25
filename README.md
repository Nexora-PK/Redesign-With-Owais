# Nexify Redesign - Frontend UI/UX Design System

[![License: Proprietary / CC-BY-4.0](https://img.shields.io/badge/License-Proprietary%20|%20CC--BY--4.0-red.svg)](LICENSE)
[![Usage](https://img.shields.io/badge/Usage-Free%20to%20Install%20&%20Use-brightgreen.svg)](#license--ownership)
[![AI Compatibility](https://img.shields.io/badge/AI%20Tools-Antigravity%20|%20Claude%20|%20Cursor%20|%20ChatGPT-blue.svg)](#installation--setup)

A cross-platform design plugin and skill that turns generic, AI-generated ("vibecoded") web interfaces into deliberate, beautifully designed products with authentic character. Compatible with **Google Antigravity**, **Claude Desktop**, **Claude Code**, **Cursor**, **ChatGPT**, and **Windsurf**.

---

## ⚡ What Nexify Redesign Does

- **Eliminates AI-Slop Tells:** Strips away purple gradient text, glowing neon blobs, emoji labels, glossy glassmorphism, and bloated margins.
- **Enforces Quiet Chrome:** Keeps backgrounds, navigation, buttons, and borders calm and neutral (tinted darks/lights + 1 primary accent).
- **Injects Focused Richness:** Concentrates visual craft into 1–2 focal moments (rendered objects, realistic app screenshots, or clean data charts).
- **Strict 5-Pass Refactoring Order:**
  1. *Spacing & Rhythm* (strict 4px/8px grid)
  2. *Copy & Voice* (natural sentence case, zero buzzwords)
  3. *Typography* (deliberate heading/sans pairings)
  4. *Color* (high contrast, calm background)
  5. *Details* (crisp 1px borders, subtle shadows)

---

## 📂 Repository Structure

```text
Nexify-Redesign/
├── plugin.json                              # Universal plugin manifest
├── README.md                                # Setup & usage documentation
├── LICENSE                                  # License & attribution
├── skills/
│   └── nexify-redesign/
│       ├── SKILL.md                         # Main skill with YAML frontmatter
│       ├── references/                      # Signs, tokens, RTL, visual patterns
│       └── scripts/                         # Automation & inspection scripts
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

#### Global Install (All Projects):
```powershell
git clone https://github.com/Nexora-PK/Nexify-Redesign.git "$HOME\.gemini\config\plugins\nexify-redesign"
```

#### Workspace-Only Install:
```bash
mkdir -p .agents/plugins
git clone https://github.com/Nexora-PK/Nexify-Redesign.git .agents/plugins/nexify-redesign
```

---

### 2. Claude Desktop App
1. Download or get `Nexify-Redesign.zip`.
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
Copy the `.mdc` file to your project's rules:
```bash
mkdir -p .cursor/rules
cp adapters/cursor/nexify-redesign.mdc .cursor/rules/nexify-redesign.mdc
```

---

### 5. ChatGPT / Custom GPTs / Claude.ai Projects
* **Custom GPTs:** Upload `skills/nexify-redesign/SKILL.md` to **Knowledge** and paste `adapters/system-prompts/nexify-redesign-prompt.txt` into **Instructions**.
* **Claude Projects:** Upload `SKILL.md` to Project Knowledge.

---

## 💡 Suggested Prompts

- *"Redesign and polish this frontend screen with Nexify Redesign."*
- *"Audit this UI for AI tells and fix spacing, typography, and color palette."*
- *"Turn this vibecoded landing page into a clean, custom-designed interface."*

---

## 📄 License & Ownership

**Copyright © 2026 Nexora PK / Owais Kayani. All Rights Reserved.**
Based on unslop by Damir Sokolovsky (licensed under CC BY 4.0).
- Free to clone, download, install, and execute for personal and commercial projects.
- Unauthorized re-hosting, re-branding, or distribution under another name is strictly prohibited.
