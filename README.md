# CoFiE project page

Official project page for **CoFiE: Coarse-to-Fine Evidence Selection for Efficient Streaming Video Understanding** (EMNLP 2026).

**Project page:** [https://SignalIsPuPuPu.github.io/cofie_proj_page/](https://SignalIsPuPuPu.github.io/cofie_proj_page/)

## Local development

Requirements: Node.js 24 or later.

```bash
npm ci
npm run dev
```

The local preview is served at `http://localhost:4321`.

## Build

```bash
npm run build
```

The production site is written to `dist/`.

## GitHub Pages

The workflow in `.github/workflows/astro.yml` deploys the site whenever the `main` branch is pushed. In the GitHub repository, open **Settings → Pages** and select **GitHub Actions** as the source.

## Updating the release links

Edit `src/paper.mdx` when the arXiv record, code, model checkpoints, or video demos become public. The paper PDF is stored at `public/paper.pdf`.
