# Agentic AI for DevOps Engineers — CareerByteCode

Marketing site for the **Agentic AI for DevOps Engineers** course — a hands-on program for DevOps engineers.
Static HTML/CSS/JS — no build step, no dependencies. Designed as a sibling of the existing CareerByteCode sites and ready to drop straight into GitHub Pages.

## Pages
- `index.html` — Home (hero, what you'll master, who it's for, tech stack, learning path, **Instructors** + **Pricing** anchor sections, enrol CTA)
- `syllabus.html` — Full curriculum: 8 modules, hands-on labs, learning tracks, outcomes
- `projects.html` — 12 portfolio projects (the labs + capstone) grouped by domain
- `earn.html` — Earn & Grow: creator playbook + the evaluation → CareerByteCode freelancing-community pathway

## Deploy to GitHub Pages
1. Create a repo named **`agentic-ai-projects`** under the `careerbytecode` account.
2. Upload the entire contents of this folder to the repo root (keep the `fonts/` folder and all images alongside the HTML — do not nest them in a subfolder).
3. In the repo, go to **Settings → Pages**, set **Source = Deploy from a branch**, **Branch = `main` / `(root)`**, then **Save**.
4. After a minute the site is live at:
   **https://careerbytecode.github.io/agentic-ai-projects/**

That URL is already set as the canonical / Open Graph URL across all pages.

## Editing notes
- **Instructor photos:** two mentors, Manoj Savukar (`manoj-480.jpg/webp`) and Sourabh Bhoyar (`sourabh-480.jpg/webp`). To swap either, replace the matching 3:4 portrait (~480×640).
- **WhatsApp:** every CTA links to `wa.me/917620774352` (IN +91) and `wa.me/32470550928` (Intl +32).
- **Shared system:** `shared-premium.css` and `shared-premium.js` carry the common components; page-specific styles live in each page's inline `<style>`. The JS handles the nav, theme toggle, accordion, scroll reveals and count-up stats.

© 2025 CareerByteCode.
