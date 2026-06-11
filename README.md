# FlowPilot · AI copilots

A single-file, zero-dependency marketing site for **FlowPilot** — a dark-mode AI copilot platform that connects to your tools, trains on your data, and runs support, sales, operations and reporting from one place.

Built as one self-contained `index.html` (all HTML, CSS and JS inline) so it deploys anywhere static.

## Highlights

- **Product-first hero** with a live, animated product dashboard (KPIs, color-coded activity feed, an in-app copilot conversation).
- **Four copilots**, each with its own accent and a mini chat preview — Support (blue), Sales (green), Operations (orange), Analytics (purple).
- **Platform bento**, integrations logo grid, frontier-model layer, process steps, and an ROI + CTA section.
- **Flagship FlowPilot Assistant** — a large centered modal (launched from the bottom-left button or *Start free*) with status badges, suggested actions and structured, status-driven responses.
- **Per-copilot modals** — themed, accent-matched assistants opened from the copilot cards.
- **Book-a-demo** popup with a clean request form.
- Matte-black + ember-orange design language, glassy surfaces, neumorphic section labels, count-up stats and reveal-on-scroll motion.

## Run locally

It's a static page — no build step.

```bash
# from this folder
python -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` directly in a browser.

## Deploy

Any static host works (Vercel, Netlify, GitHub Pages, Cloudflare Pages). Point it at this folder; `index.html` is the entry.

## Tech

- Plain HTML / CSS / vanilla JS — no frameworks, no dependencies
- Inter + Inter Tight + JetBrains Mono via Google Fonts
- Inline SVG icons and logos

---

A **Frameflows** studio project. Developed by **Shashwat**.
