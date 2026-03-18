# 🏢 Mission Control Dashboard

> A custom-built, real-time operations dashboard for monitoring AI agents, projects, and business metrics — built as part of a self-hosted multi-agent AI infrastructure.

![Dashboard Preview](screenshots/dashboard-main.png)

---

## 🎯 Overview

Mission Control is a single-page web dashboard built for **MODTECH Ventures** — the operational hub for monitoring a multi-agent AI system running on a Linux VPS. It provides a centralized view of agent activity, project status, and key business metrics across all active operations.

---

## ✨ Features

- **Agent Status Panel** — Live status cards for each AI agent (Roni, Robo, Star, Yoshi) with role, model, and channel bindings
- **Project Tracker** — Status tiles for all active projects (MODTECH FBA, Tech Motivates, Peptide Tracker)
- **Metrics Overview** — KPI cards with trend indicators for business performance tracking
- **Dark Mode UI** — Full dark theme with glass-morphism card effects, custom CSS variables, and smooth transitions
- **Responsive Layout** — CSS Grid layout adapts to different screen sizes

---

## 🔧 Tech Stack

- **Claude Code (Anthropic)** — AI coding agent used to scaffold, debug, and iteratively refine the entire dashboard
- **OpenClaw** — Multi-agent AI orchestration platform that directed Claude Code and managed the development workflow
- **Claude Sonnet / Claude Opus** — LLMs used for code generation, UI reasoning, and architecture decisions
- **OpenAI Codex** — Code completion and generation for JavaScript logic
- **HTML5** — Semantic structure
- **CSS3** — Custom properties (variables), CSS Grid, Flexbox, glass-morphism effects, keyframe animations
- **Vanilla JavaScript** — Dynamic rendering, no external framework dependencies
- **Google Fonts (Inter)** — Typography

---

## 🗂️ File Structure

```
mission-control/
├── index.html          # Main dashboard (self-contained, all CSS + JS inline)
├── README.md           # This file
└── screenshots/        # Dashboard preview images
    └── dashboard-main.png
```

---

## 🚀 Running Locally

No build step required — open `index.html` directly in any browser:

```bash
# Clone the repo
git clone https://github.com/roccopaz/mission-control.git

# Open in browser
open index.html
# or on Linux:
xdg-open index.html
```

---

## 💡 What I Built & Learned

- Built using **AI-assisted development** with **Claude Code** (Anthropic's CLI coding agent) and **OpenClaw**, applying prompt engineering and iterative refinement to produce a production-quality dashboard — demonstrating practical understanding of LLM coding workflows and model capability tradeoffs
- Applied deliberate **model selection**: Claude Sonnet for fast day-to-day orchestration, Claude Opus for complex reasoning, and OpenAI Codex for code generation — making real cost/speed/capability tradeoffs
- Designed a complete dark-mode dashboard UI using HTML, CSS, and JavaScript — implementing CSS custom properties (variables) for consistent theming across 1200+ lines of code
- Used CSS Grid for multi-column responsive layouts with card-based components and glass-morphism effects
- Structured a large single-file application with clear architecture and maintainable, well-commented code

---

## 🔌 API Integrations

Mission Control connects to real external APIs to pull live data:

| API | Purpose |
|-----|---------|
| **Amazon SP-API** | Syncs live units sold, order count, and revenue directly from the MODTECH FBA business |
| **YNAB Budgeting API** | Pulls expense categories, tracks MODTECH spend, and calculates net P&L automatically |
| **Brave Search API** | Powers the trending intel feed — fetches latest AI news, market trends, and research signals |
| **Postiz API** | Connects the content calendar — pulls scheduled and published posts across YouTube and TikTok |
| **ISS Tracker API** | Real-time International Space Station position, speed, and crew data displayed in the dashboard |
| **Kanye REST API** | Injects motivational quotes into the dashboard header on load |

---

## 🔗 Related Projects

- [OpenClaw VPS AI System](https://roccopaz.github.io) — the platform this dashboard monitors
- [Portfolio](https://roccopaz.github.io) — full project breakdown

---

*Built as part of a self-hosted multi-agent AI infrastructure — Texas State University CIS Senior*
