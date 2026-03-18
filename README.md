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

- **HTML5** — Semantic structure
- **CSS3** — Custom properties (CSS variables), CSS Grid, Flexbox, glass-morphism effects, animations
- **Vanilla JavaScript** — Dynamic data rendering, no external framework dependencies
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

- Designed a complete dark-mode dashboard UI from scratch using only HTML/CSS/JS
- Implemented CSS custom properties (variables) for consistent theming across 1200+ lines of code
- Used CSS Grid for multi-column responsive layouts with card-based components
- Built glass-morphism card effects using `rgba` backgrounds, `backdrop-filter`, and layered borders
- Structured a large single-file app with clear section comments and maintainable architecture

---

## 🔗 Related Projects

- [OpenClaw VPS AI System](https://roccopaz.github.io) — the platform this dashboard monitors
- [Portfolio](https://roccopaz.github.io) — full project breakdown

---

*Built as part of a self-hosted multi-agent AI infrastructure — Texas State University CIS Senior*
