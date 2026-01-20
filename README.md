# ocryptocode

Oussama Rafouk



I am the CEO villager of https://x.com/vortex_capital_ , ambassador, and community builder..

I build a coding legacy — projects that reflect my passion. These repositories act as proof-of-work (POW) and are part of one unified ecosystem

This repository also serves as my resume, it's the beginning of everything 


https://x.com/Oussama_buildin 



## Projects Showcase 

### VORTEX
An ecosystem of crypto projects, deals, and events. Funded rounds, sponsors welcomed — we also create new coins inside VORTEX.

### PPH
An app that interprets queries and classifies financial data. An efficient way to stay updated with financial information.

### CPT
A platform that tracks cryptocurrency price movements in real time. Powerful for monitoring market updates and sharing on social channels.

Repo: https://github.com/ocryptocode/crypto-price-tracker

### aalex
An artificial intelligence that helps with everything

https://github.com/ocryptocode/aalex 
---

## Design templates
A collection of design and UI templates you can reuse across projects (landing pages, components, social assets, email templates, etc.)

- Canonical folder: `/templates/`
- Example template types: HTML/CSS, React components, Figma exports, social images (PNG/SVG), email templates.

How to add a template:
1. Create a file under `/templates/`, e.g. `/templates/landing-basic.html` or `/templates/twitter-card.svg`.
2. Add usage notes inside the template file or include a small markdown file alongside it, e.g. `/templates/landing-basic/README.md`.
3. Commit and push.

Example:
```bash
mkdir -p templates/landing-basic
echo "<!-- Landing template -->" > templates/landing-basic/index.html
git add templates/landing-basic
git commit -m "Add landing-basic template"
git push origin main
```

Tip: Keep templates small, documented, and include a preview image (preview.png) inside the template folder.

---

## Achievements
A curated list of milestones, launches, events, and recognitions related to VORTEX and my work. Use this to show progress, wins, and credibility.

Recommended storage approaches:
- Simple: Add a markdown list inside README (below).
- Structured: Create `/achievements/` with one file per achievement (`YYYY-MM-DD-title.md`) and an index (`/ACHIEVEMENTS.md`) that lists them.
- Metadata: Use YAML frontmatter inside each achievement file to standardize date, links, and tags.

Example achievement item (in README):
- 2025-04-20 — Launched CPT v1.0 — Public alpha, 5k users in first week. (link)
- 2024-12-01 — Vortex Seed Round — Raised $X from sponsors. (link)

Example achievement file structure (`/achievements/2025-04-20-launched-cpt.md`):
```markdown
---
title: "Launched CPT v1.0"
date: "2025-04-20"
links:
  - url: "https://github.com/ocryptocode/crypto-price-tracker"
    label: "Repo"
tags:
  - launch
  - product
---

Public alpha, 5k users in first week. Short description of the milestone and significance.
```

Badge example (use shields.io):
```markdown
![Launched](https://img.shields.io/badge/achievement-Launched-brightgreen)
```

How to add an achievement:
```bash
mkdir -p achievements
cat > achievements/2025-12-06-some-achievement.md <<'EOF'
---
title: "Example Achievement"
date: "2025-12-06"
links:
  - url: "https://example.com"
    label: "Details"
tags:
  - example
---
Short description about the achievement and any relevant links.
EOF

git add achievements
git commit -m "Add achievement: Example Achievement"
git push origin main
```

---

## Example README snippet — Templates & Achievements (copy/paste)
Add this small section anywhere in your README to surface both features:

### Templates
- Browse templates: /templates
- To use: clone repo and copy the template you need.

### Achievements
- Browse achievements: /achievements or update this README's Achievements section.
- Add a new achievement file and link to public posts/releases.

---

## Repo structure (recommended)
- /templates/            # design templates, grouped by type
- /achievements/         # one file per achievement with metadata
- /projects/             # project-specific code if you want to centralize
- README.md              # this file — high level overview and links

---

## Tips & next steps
- Keep templates small, clearly named, and include a README or usage notes for each template.
- Use consistent date-based filenames for achievements so they sort chronologically.
- Consider using GitHub Releases or the repository's Projects/Discussions to highlight important launches and link back to achievements.
- If you want visual badges for major achievements, use shields.io and include them at the top of README.

---

If you'd like, I can:
- create `/templates/` and add 2 example templates (HTML + social image preview),
- create `/achievements/` and add one sample achievement file,
- open a branch and prepare a PR with the README changes.

Tell me whether you want me to push files and which branch (or I can open a PR against `main`).
