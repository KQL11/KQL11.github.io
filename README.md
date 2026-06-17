# Personal homepage — Kaiqing Lin

Static site: `index.html` + `style.css`. No build step, no dependencies.

## Preview locally
Double-click `index.html` (opens in your browser). Keep `index.html` and `style.css` in the same folder.

## Deploy to GitHub Pages
1. Create a repo named **`YOUR-USERNAME.github.io`** (use your real GitHub username).
2. Put `index.html`, `style.css` (and `photo.jpg`, `cv.pdf` if you add them) in the repo root.
3. Push, then go to **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main` / folder `/root`.
4. Visit `https://YOUR-USERNAME.github.io` (live in ~1 minute).

## Things to fill in (search index.html for these)
- `photo.jpg` — add a square headshot to the folder (falls back to a soft gradient if missing).
- `cv.pdf` — add your CV; the "Download CV" button links to it.
- `YOUR-ID@email.szu.edu.cn` — your full institutional email.
- `https://github.com/YOUR-USERNAME` — your GitHub.
- `https://www.linkedin.com/in/YOUR-PROFILE` — your LinkedIn (or delete the line).
- **News** section — edit/add items as things change.

## Publication teaser figures
Each paper in the "As (co-)first author" group shows a teaser image. Drop these 6 files into the
same folder (any image format works — just keep the `.png` name, or change the `src` in `index.html`):

- `fig-icml.png` — ICML 2026 (Deep-VRM)
- `fig-cvpr.png` — CVPR 2026 (Unified-GRPO)
- `fig-neurips.png` — NeurIPS 2025 (VIP Guard)
- `fig-arxiv.png` — Seeing Before Reasoning
- `fig-aaai.png` — AAAI 2025 (Reprogramming VLM)
- `fig-tifs.png` — IEEE TIFS 2024 (KDNFT)

If a file is missing, that figure is automatically hidden — the rest of the card still shows.

Metrics (232 citations / h-index 8 / i10 5) and publications reflect your Google Scholar as of June 2026 — update the numbers in `index.html` periodically.
