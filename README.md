# Linke Tree

Personal link-in-bio landing page for Abdulaziz Hkeem (Azowz).  
Built as a single HTML file with a glassmorphic aesthetic, responsive grid, dynamic status panel, and curated calls to action including GitHub, Kaggle, LinkedIn, Hugging Face, and resume download.

## Features
- Modern UI with Inter font, layered gradients, subtle motion, and light/dark toggle.
- Highlight panel that showcases current focus plus KPI cards (models shipped, latency, markets covered).
- Modular link cards with icons, hover states, and optional grid layout for projects.
- Fully responsive down to mobile with simplified spacing and stacked metrics.
- Pure HTML/CSS/vanilla JS for zero build tooling and ultra-fast hosting on any static provider.

## Getting Started
1. Clone or download this repository.
2. Open `index.html` in any browser to preview locally.
3. Host the same file on GitHub Pages, Vercel, Netlify, or any static host — no build step required.

## Customization
- **Profile details:** Update the hero block inside `index.html` (name, avatar URL, badges, tagline).
- **Status & metrics:** Edit the `.status-panel` copy and `.stat-card` values to reflect current initiatives.
- **Links:** Duplicate an existing `.link` block to add more profiles or projects. Icons use inline SVGs for easy swapping.
- **Styling:** Global tokens live in the `:root` section; adjust gradients, colors, spacing, or animations directly there.

## Deployment Tips
- Commit `index.html`, `avatar.jpg`, and `resume.pdf` together so hosted versions stay in sync.
- For GitHub Pages, push to `main` and enable Pages → choose `main` + `/root`.
- To use a custom domain, configure your DNS to point at the chosen static host and add the appropriate config file (e.g., `CNAME` for GitHub Pages).

## License
Released under the MIT License. See `LICENSE` for details.
