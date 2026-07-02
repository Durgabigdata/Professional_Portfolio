# Portfolio — Durgaprasad Kakara

AI/ML Engineer portfolio website — single-page HTML, dark mode, blue accent, responsive.

---

## Table of Contents

- [Build Summary](#build-summary)
- [Tech Stack Decision](#tech-stack-decision)
- [Project Structure](#project-structure)
- [Sections Included](#sections-included)
- [Design Specs](#design-specs)
- [Placeholders — Fill Before Deploy](#placeholders--fill-before-deploy)
- [Deployment Guide — GitHub Pages](#deployment-guide--github-pages)
  - [Step 1: Create a GitHub Repository](#step-1-create-a-github-repository)
  - [Step 2: Upload Files](#step-2-upload-files)
  - [Step 3: Enable GitHub Pages](#step-3-enable-github-pages)
  - [Step 4: Add Resume PDF (Later)](#step-4-add-resume-pdf-later)
  - [Step 5: Custom Domain (Optional)](#step-5-custom-domain-optional)
- [TODOs / Future Improvements](#todos--future-improvements)

---

## Build Summary

| Item | Detail |
|------|--------|
| **Candidate** | Durgaprasad Kakara |
| **Role** | AI/ML Engineer |
| **File** | `index.html` (single-file) |
| **Size** | ~21 KB, 367 lines |
| **Favicon** | Inline SVG data URI (no extra file) |
| **Build time** | ~2 minutes |
| **Deployment** | GitHub Pages |

---

## Tech Stack Decision

**Question:** What should we build it with?

**Answer:** Single-page HTML + CSS + JS (no frameworks, no build tools).

**Why:**
- Fastest to create — zero dependencies, zero build step
- Deployable in under 2 minutes to GitHub Pages
- Looks professional with dark mode, cards, timeline
- Easy to maintain and edit later

---

## Project Structure

```
portfolio/
  index.html      # Main portfolio page (all CSS/HTML inline)
  README.md       # This file
```

No `favicon.ico` needed — the icon is embedded as a data URI inside `<head>`.

---

## Sections Included

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Name, title, tagline, 4 action buttons (Download Resume, GitHub, LinkedIn, Contact Me) |
| 2 | **About Me** | Bio + current areas of interest (10 tags) |
| 3 | **Experience Timeline** | Vertical timeline: 2023 GET → 2024 Certification → 2025 Data Scientist → 2026 AI/ML Trainee |
| 4 | **Skills** | 7 category cards: Programming, ML, Gen AI, Frameworks, Cloud & DBs, Libraries & Tools, LLM Providers |
| 5 | **Featured Projects** | CoreLynx AI, HR AI Voice Interview Platform, mTouch AI Assistant, Agent Auto Assignment Engine |
| 6 | **Education** | RGUKT — B.Tech Mechanical Engineering (2023) |
| 7 | **Certification** | ExcelR — Professional Data Science Certification |
| 8 | **GitHub** | 4 placeholder repo cards (links open in new tab) |
| 9 | **Resume** | Download button (placeholder) |
| 10 | **Contact** | Email, Phone, LinkedIn, GitHub |
| 11 | **Footer** | Copyright 2026 |

---

## Design Specs

- **Theme:** Dark mode (`#0f172a` background)
- **Cards:** `#1e293b` with hover accent border
- **Accent color:** `#3b82f6` (blue)
- **Font:** Inter (Google Fonts), system fallback
- **Layout:** Max-width 1000px centered, responsive grid
- **No:** Animations, particles, gradients, skill bars
- **Responsive:** Single column on mobile (`≤768px`)

---

## Placeholders — Fill Before Deploy

The following fields contain dummy/placeholder values. Replace them with your real details before deploying (or ask me to do it for you).

| Field | Current Value | Real Value Needed |
|-------|--------------|-------------------|
| GitHub profile URL | `https://github.com/` | e.g. `https://github.com/durgaprasad-k` |
| LinkedIn profile URL | `https://linkedin.com/in/` | e.g. `https://linkedin.com/in/durgaprasad-k` |
| Email | `your.email@example.com` | Your real email |
| Phone | `+91-XXXXXXXXXX` | Your real phone number |
| Resume download link | `#` (no file) | `resume.pdf` (upload separately) |
| Repo links (GitHub section) | `https://github.com/` | Real repo URLs |
| Repo names | "Repository 1", etc. | Real repo names |

---

## Deployment Guide — GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to https://github.com/new
2. Repository name: `portfolio` (or `username.github.io` for a user site)
3. Keep it **Public**
4. Do NOT initialize with README (we already have one)
5. Click **Create repository**

### Step 2: Upload Files

```bash
# Option A — Upload via browser
```
1. On the repo page, click **Add file → Upload files**
2. Drag and drop `index.html` and `README.md`
3. Click **Commit changes**

```bash
# Option B — Upload via Git CLI (if you have Git installed)
cd "C:\Users\lapto\Downloads\portfolio"
git init
git add .
git commit -m "Initial portfolio commit"
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Branch**, select `main` and folder `/ (root)`
4. Click **Save**
5. Wait ~1–2 minutes. Your site will be live at:
   `https://YOUR-USERNAME.github.io/portfolio/`

If you named the repo `YOUR-USERNAME.github.io`, the URL will be:
`https://YOUR-USERNAME.github.io/`

### Step 4: Add Resume PDF (Later)

1. Upload `resume.pdf` to the repository
2. Update the resume download link in `index.html`:
   ```html
   <a href="resume.pdf" class="btn btn-primary" download>Download Resume</a>
   ```

### Step 5: Custom Domain (Optional)

1. Buy a domain (e.g., via Namecheap, Google Domains)
2. In GitHub Pages settings, enter your domain under **Custom domain**
3. Add a CNAME record at your DNS provider pointing to `YOUR-USERNAME.github.io`

---

## TODOs / Future Improvements

- [ ] Replace all placeholder values with real data
- [ ] Upload `resume.pdf`
- [ ] Add real GitHub repo links and descriptions
- [ ] Generate architecture diagrams via Gemini and embed them
- [ ] (Optional) Add Google Analytics
- [ ] (Optional) Add Open Graph meta tags for social sharing

---

## Conversation Reference

This document was generated from a conversation between **Durgaprasad Kakara** and **opencode** (the AI assistant) on **July 1, 2026**. The full conversation included:

- Requirements gathering (portfolio type, sections, design preferences)
- Specification discussion (missing items identified: tech stack, deployment, resume PDF, GitHub links, contact form, favicon, SEO)
- Build plan approval
- Implementation (single-file HTML with all sections)
- Deployment walkthrough

---

*Last updated: July 1, 2026*
