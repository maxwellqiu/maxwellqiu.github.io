# maxwellqiu.github.io

Personal professional website for **Wenyang Qiu** — Data Quality Developer | Data Scientist.

Built with [Jekyll](https://jekyllrb.com/) + [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme, hosted on GitHub Pages.

---

## 🚀 Quick Start (Local Development)

### Prerequisites
- Ruby 3.x
- Bundler (`gem install bundler`)

### Setup

```bash
git clone https://github.com/maxwellqiu/maxwellqiu.github.io.git
cd maxwellqiu.github.io
bundle install
bundle exec jekyll serve --livereload
```

Visit `http://localhost:4000` in your browser.

---

## 📁 Project Structure

```
.
├── _config.yml              # Site config, author info, theme settings
├── _data/
│   └── navigation.yml       # Top navigation links
├── _pages/
│   ├── about.md             # Homepage / bio
│   ├── resume.md            # HTML resume
│   ├── projects.md          # Project card grid
│   └── contact.md           # Contact links
├── _projects/               # One .md file per project
│   ├── login-monitor.md
│   ├── appium-suite.md
│   └── ...
├── _sass/
│   └── custom.scss          # Color palette, typography, component styles
├── assets/
│   ├── css/main.scss        # SCSS entry point
│   ├── images/profile.jpg   # ← Upload your photo here
│   └── resume.pdf           # ← Upload your PDF resume here
└── .github/workflows/
    └── jekyll.yml           # GitHub Actions auto-deploy
```

---

## ✏️ Personalizing the Site

### 1. Update your info in `_config.yml`
- Replace `your.email@example.com` with your real email
- Update `author.bio` with your own description
- Confirm your name, LinkedIn, GitHub URLs

### 2. Upload your assets
```bash
# Profile photo (square recommended, min 200x200)
cp your-photo.jpg assets/images/profile.jpg

# Resume PDF
cp your-resume.pdf assets/resume.pdf
```

### 3. Fill in your Resume (`_pages/resume.md`)
Replace placeholder text with your real:
- Work experience entries
- Education
- Certifications

### 4. Replace DS project stubs (`_projects/ds-project-1.md`)
Update `title`, `description`, `stack`, `github`, and the page body.

### 5. Update Contact email (`_pages/contact.md`)
Replace `your.email@example.com` with your real email address.

---

## ➕ Adding a New Project

Create a new file in `_projects/`:

```markdown
---
title: "My New Project"
category: "Data Science"   # or "QA Automation"
description: "Two sentence description for the project card."
stack:
  - Python
  - pandas
order: 5                   # controls card sort order
github: "https://github.com/maxwellqiu/my-project"
demo: "https://myapp.com"  # optional
---

## Your full project writeup goes here...
```

---

## 🚢 Deployment

Push to `main` — GitHub Actions automatically builds and deploys to GitHub Pages.

Make sure GitHub Pages is configured to use **GitHub Actions** as the source:
`Settings → Pages → Source → GitHub Actions`

---

## 🎨 Customizing Colors

Edit `_sass/custom.scss` and update the CSS variables at the top:

```scss
:root {
  --accent: #e94560;   /* Change this to your preferred accent color */
}
```

---

## License

Content © Wenyang Qiu. Theme: [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) (MIT).
