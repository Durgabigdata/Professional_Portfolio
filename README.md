# Portfolio — Durgaprasad Kakara

AI/ML Engineer portfolio website — single-page HTML, dark mode, blue accent, responsive.

**Live URL:** https://Durgabigdata.github.io/Professional_Portfolio/

---

## Table of Contents

- [Build Summary](#build-summary)
- [Tech Stack Decision](#tech-stack-decision)
- [Project Structure](#project-structure)
- [Sections Included](#sections-included)
- [Design Specs](#design-specs)
- [Deployment Info](#deployment-info)
- [TODOs / Future Improvements](#todos--future-improvements)

---

## Build Summary

| Item | Detail |
|------|--------|
| **Candidate** | Durgaprasad Kakara |
| **Role** | AI/ML Engineer |
| **File** | `index.html` (single-file) |
| **Size** | ~23 KB, 886 lines |
| **Favicon** | Inline SVG data URI (no extra file) |
| **Images** | Profile photo + 4 project screenshots + resume PDF |
| **Build time** | ~2 minutes |
| **Deployment** | GitHub Pages |
| **Repo** | https://github.com/Durgabigdata/Professional_Portfolio |
| **Live URL** | https://Durgabigdata.github.io/Professional_Portfolio/ |

---

## Tech Stack Decision

**Answer:** Single-page HTML + CSS + JS (no frameworks, no build tools).

**Why:**
- Fastest to create — zero dependencies, zero build step
- Deployable in under 2 minutes to GitHub Pages
- Looks professional with dark mode, cards, timeline, icons, animations
- Easy to maintain and edit later

---

## Project Structure

```
Professional_Portfolio/
  index.html                               # Main portfolio page
  README.md                                # This file
  Profile.png                              # Profile photo
  corelynx.png                             # CoreLynx AI project screenshot
  Hr voice agent.png                       # HR Voice Interview project screenshot
  mtouch chatbot.png                       # mTouch AI Assistant project screenshot
  agent engine.png                         # Agent Auto Assignment project screenshot
  Durgaprasad_Kakara_AIML_Engineer_Resume.pdf  # Resume PDF
```

No `favicon.ico` needed — the icon is embedded as a data URI inside `<head>`.

---

## Sections Included

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Profile photo, name, title, tagline, 4 action buttons (Download Resume, GitHub, LinkedIn, Contact Me) |
| 2 | **About Me** | Bio + current areas of interest (10 tags) |
| 3 | **Experience Timeline** | Vertical timeline with icons: 2023 GET → 2024 Certification → 2025 Data Scientist → 2026 AI/ML Trainee |
| 4 | **Skills** | 7 category cards with progress bars + icons: Programming, ML, Gen AI, Frameworks, Cloud & DBs, Libraries & Tools, LLM Providers |
| 5 | **Featured Projects** | CoreLynx AI, HR AI Voice Interview Platform, mTouch AI Assistant, Agent Auto Assignment Engine (with screenshots) |
| 6 | **Education** | RGUKT — B.Tech Mechanical Engineering (2023) |
| 7 | **Certification** | ExcelR — Professional Data Science Certification |
| 8 | **GitHub** | 4 repo cards (links to GitHub profile) |
| 9 | **Resume** | Download button with PDF |
| 10 | **Contact** | Email, Phone, LinkedIn, GitHub (with icons) |
| 11 | **Footer** | Copyright 2026 |

---

## Design Specs

- **Theme:** Dark mode (`#0f172a` background)
- **Cards:** `#1e293b` with hover lift + blue glow shadow
- **Accent color:** `#3b82f6` (blue), gradient to `#8b5cf6` (purple)
- **Font:** Inter (Google Fonts), system fallback
- **Layout:** Max-width 1000px centered, responsive grid
- **Animations:** Scroll-triggered fade-in sections, card hover lift
- **Background:** Subtle dot pattern via CSS radial-gradient
- **Icons:** Inline SVG icons throughout (no external library)
- **Responsive:** Single column on mobile (`≤768px`)

---

## Deployment Info

### Repository
- **Platform:** GitHub Pages
- **Repo:** https://github.com/Durgabigdata/Professional_Portfolio
- **Live URL:** https://Durgabigdata.github.io/Professional_Portfolio/

### How it was deployed
1. Created a public repo `Professional_Portfolio` on GitHub
2. Initialized git locally and committed all files
3. Pushed to `main` branch
4. Enabled GitHub Pages in repo Settings → Pages → Deploy from branch `main` / `(root)`

### Updating the site
```bash
cd "C:\Users\lapto\Downloads\portfolio"
git add .
git commit -m "Your update message"
git push
```
GitHub Pages auto-deploys from the `main` branch. Changes are live in ~1-2 minutes.

---

## TODOs / Future Improvements

- [x] Replace LinkedIn, GitHub, email, phone with real data
- [x] Upload resume PDF and link it
- [x] Add profile photo and project screenshots
- [ ] Replace 4 placeholder repo cards with real repo names, descriptions and URLs
- [ ] (Optional) Add Google Analytics
- [ ] (Optional) Add Open Graph meta tags for social sharing
- [ ] (Optional) Custom domain

---

*Last updated: July 2, 2026*
