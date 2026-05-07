<div align="center">

# Yashwanth Chowdary

### DevOps Engineer — Portfolio Site

A single-file animated portfolio.
Cinematic dark, orange glow, terminal energy.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Single File](https://img.shields.io/badge/single--file-no%20build-ff7a1f?style=flat-square)
![Responsive](https://img.shields.io/badge/responsive-yes-4ade80?style=flat-square)

</div>

---

## Contents

- [Quick start](#quick-start)
- [What's inside](#whats-inside)
- [Personalize before publishing](#personalize-before-publishing)
- [Hosting](#hosting)
- [Design tokens](#design-tokens)
- [What's intentionally different from the reference video](#whats-intentionally-different-from-the-reference-video)

---

## Quick start

**Just open it.** Double-click `index.html`. No build, no install, no dependencies beyond Google Fonts.

To preview while editing, run a tiny local server:

```bash
# Python
python3 -m http.server 8080

# OR Node
npx serve .
```

Then visit `http://localhost:8080`.

---

## What's inside

| Section | What it does |
|---|---|
| **Top ticker** | Auto-scrolling system telemetry — `system.status: operational`, `uptime: 99.97%`, etc. |
| **Hero** | Name, role pills, description, animated stylized character with breathing, blinking and head tilt. |
| **About** | 4 stat cards on the left, prose narrative on the right. |
| **Work** | 6 projects in a list view — 3 real GitHub forks + 3 credible "in progress / planned" placeholders. |
| **Stack** | 6 skill categories: orchestration, CI/CD & GitOps, infra & cloud, observability, languages, methodology. |
| **Journey** | Left-aligned timeline with 5 entries and an animated dot on the current role. |
| **Certs** | 4 certifications in a 2-column grid (Harness, Qniverse, Tech Mahindra, ICorr). |
| **Contact** | Closing statement + 3 channel cards (email, LinkedIn, GitHub). |
| **Custom cursor** | Orange dot + ring that grows when hovering links. Auto-disabled on touch. |

---

## Personalize before publishing

Before pushing this live, swap a few placeholders for your real info:

### Must change

- [ ] **Email** — replace both `mailto:yashwanth@example.com` instances with your real address
- [ ] **Project rows 03, 05, 06** — these are filler (GitOps, Observability, Terraform). Replace with real repos when you build them. The `href="#"` is intentional so they don't 404.
- [ ] **Stat numbers** in the About section (`10+`, `5+`, `2024`, `∞`) — adjust to honest counts

### Nice to verify

- [ ] **Cert dates** — confirm the issued years on the four certifications
- [ ] **`last_deploy: 2025.11.14`** in the ticker — bump it or remove
- [ ] **Project descriptions** — punch them up with real metrics from your work

---

## Hosting

### Option 1 — GitHub Pages (recommended)

You already have a GitHub account. This is the easiest path.

```bash
git init
git add index.html README.md
git commit -m "DevOps portfolio"
git branch -M main
git remote add origin https://github.com/YashwanthChowdary05/portfolio.git
git push -u origin main
```

Create a repo named exactly `portfolio` on GitHub before pushing.
Live at `https://yashwanthChowdary05.github.io` within ~1 minute.

### Option 2 — Netlify

1. Go to [netlify.com](https://netlify.com)
2. Drag the folder containing `index.html` onto the dashboard
3. Get a free `*.netlify.app` URL instantly

### Option 3 — Vercel

Same idea — [vercel.com](https://vercel.com) → import folder or connect a GitHub repo. Free hobby tier.

---

## Design tokens

All theming lives in CSS variables at the top of the `<style>` block. Tweak these to retheme everything at once:

```css
--bg:         #0a0807;   /* page background           */
--bg-soft:    #110e0c;   /* alt section background    */
--bg-card:    #181513;   /* card surfaces             */

--orange:     #ff7a1f;   /* primary accent            */
--orange-hot: #ff9447;   /* hover / hot state         */
--ember:      #ff5a1f;   /* deep glow                 */
--amber:      #ffb74d;   /* warm highlight            */

--text:       #f5ede4;   /* primary text              */
--text-dim:   #a89c8e;   /* secondary text            */
--text-faint: #6b6258;   /* tertiary / labels         */
```

### Typography

| Use | Font | Source |
|---|---|---|
| Display headings | **Fraunces** (italic-friendly serif) | Google Fonts |
| Body text | **Manrope** | Google Fonts |
| Terminal labels | **JetBrains Mono** | Google Fonts |

### Animation

- **Easing** — `cubic-bezier(0.16, 1, 0.3, 1)` (Apple-style) for entrances
- **Stagger** — each section reveals its children with 80ms delays so things don't all fire at once
- **Reduced motion** — visitors with the OS accessibility setting get a static page

---

## What's intentionally different from the reference video

The video shows a generic "full-stack developer" template — large name, photo, a few project cards. This portfolio adapts the same atmospheric warmth into something fitting for **DevOps / Cloud / SRE work**:

- **Terminal-window framing** on the hero graphic instead of a glamour shot
- **Status ticker** at the top — operators read status, not slogans
- **Monospace UI labels** throughout
- **Status indicators** (`SHIPPED`, `IN PROGRESS`, `PLANNED`) on each project — honest, not theatre
- **Animated stylized character** instead of a portrait — gives personality without a photo shoot

Same cinematic warmth. Right job for the right audience.

---

<div align="center">

**Built with HTML, CSS & care.**

[GitHub](https://github.com/Yashwanth-Tek) · [LinkedIn](https://www.linkedin.com/in/yashwanth-chowdary-75376a288)

</div>
