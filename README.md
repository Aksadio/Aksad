# Shahriar Azim Aksad — Portfolio
 
> Personal portfolio website built from scratch. Dark-themed, single-file, no frameworks.
 
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-white?style=flat-square&logo=github)](https://aksadio.github.io/Aksad)
[![HTML](https://img.shields.io/badge/HTML-Single%20File-orange?style=flat-square)](index.html)
[![License](https://img.shields.io/badge/License-MIT-gray?style=flat-square)](LICENSE)
 
---
 
## Overview
 
A fully hand-coded personal portfolio for **Shahriar Azim Aksad** — AI & web developer based in Cox's Bāzār, Bangladesh. No build tools, no npm, no frameworks. Just one HTML file with everything embedded inside.
 
Built to reflect a systems-thinking aesthetic: dark, minimal, precise.
 
---
 
## Features
 
- **Animated hero** with particle canvas background and mouse-reactive lines
- **Filterable skills grid** — filter by AI & Automation, Programming, or Tools
- **Project showcase** — filterable cards with GitHub + live demo links
- **Certifications wall** — credential cards with external verification links
- **Timeline** — education, community involvement, and certifications
- **Experience section** — role cards with tech stacks and impact bullets
- **Contact form** — mailto-based submission with a success state UI
- **Command palette** — keyboard-accessible quick navigation (`⌘K`)
- **Theme toggle** — dark/light mode switch
- **Responsive layout** — mobile drawer nav, fluid typography
- **Scroll-aware navbar** — pill nav that reacts to page position
- **Smooth scroll + fade-up animations** — IntersectionObserver-driven
---
 
## Tech Stack
 
| Layer | What's Used |
|---|---|
| Markup | Semantic HTML5 |
| Styling | Vanilla CSS with CSS custom properties |
| Scripting | Vanilla JavaScript (ES6+) |
| Background | HTML Canvas API |
| Icons | Inline SVG |
| Fonts | System font stack + Courier New (mono) |
| Deployment | GitHub Pages |
 
Zero dependencies. Zero build steps.
 
---
 
## Sections
 
| # | Section | Description |
|---|---|---|
| 01 | Hero | Name, domain pills, animated background, scroll indicator |
| 02 | About | Bio, portrait, stats (6+ months, 20+ AI projects, 10+ personal projects), highlight cards |
| 03 | Skills | 14 skills across AI & Automation, Programming, and Tools — filterable with animated bars |
| 04 | Projects | 11 GitHub projects with tech tags and live links |
| 05 | Certificates | Google (Gemini), AWS, Kaggle, GDG credentials |
| 06 | Timeline | CS50x, FutureLearn, GDG Dhaka, Kaggle, AWS, Google Ads |
| 07 | Experience | 3 roles — AI Workflow Dev, Python Automation, Web Developer |
| 08 | Contact | Form with mailto submission + social links |
 
---
 
## Getting Started
 
No installation needed.
 
**Option 1 — GitHub Pages (recommended)**
Push `index.html` to a repo named `<your-username>.github.io` or enable Pages from any repo's settings. The site will be live immediately.
 
**Option 2 — Local preview**
```bash
# Clone the repo
git clone https://github.com/Aksadio/Aksad.git
cd Aksad
 
# Serve locally (avoids file:// CORS issues)
python -m http.server 8080
```
Then open `http://localhost:8080` in your browser.
 
**Option 3 — Direct open**
Double-click `index.html`. Most features work, though some browsers block local scripts.
 
---
 
## Customization
 
All content lives in the `<script>` block near the bottom of `index.html`:
 
```javascript
const skillsData = [ ... ]     // skills list
const projectsData = [ ... ]   // project cards
const certsData = [ ... ]      // certification cards
const timelineData = [ ... ]   // education & community timeline
const expData = [ ... ]        // experience roles
```
 
Edit those arrays to update content — no need to touch the HTML or CSS.
 
---
 
## Projects Showcased
 
| Project | Stack | Description |
|---|---|---|
| Aksad's profile | HTML, JS, CSS | This portfolio — repo: `Aksad` |
| phoneguard | Kotlin | Android security app |
| hacker-console | HTML | Terminal-style UI |
| constellation-explorer | JS, HTML, CSS | Interactive sky map |
| telegram-bot | Python, Docker | Dockerized Telegram bot |
| devmood | JavaScript | Developer mood tracker |
| markflow | HTML, JS, CSS | Markdown documentation tool |
| password-generator | Python, HTML | Secure password generator |
| QR | Python | QR code generator |
 
---
 
## Contact
 
| Platform | Link |
|---|---|
| Email | aksad.dev.io@gmail.com |
| GitHub | [github.com/Aksadio](https://github.com/Aksadio) |
| LinkedIn | [linkedin.com/in/shahariar-azim-aksad](https://www.linkedin.com/in/shahariar-azim-aksad-69aaaa3b8/) |
| Kaggle | [kaggle.com/shahariarazimaksad](https://www.kaggle.com/shahariarazimaksad) |
 
---
 
## License
 
MIT — free to use, fork, and adapt. Attribution appreciated but not required.
 
---
 
*Engineered from ground up for system coherence.*
 
