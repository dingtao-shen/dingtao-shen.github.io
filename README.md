# dingtao-shen.github.io

Personal academic website of **Dingtao Shen**, Ph.D. candidate at HKUST.

Built with [PRISM](https://github.com/xyjoey/PRISM) — a Next.js + Tailwind CSS + TypeScript template. All site content lives in the [`content/`](content/) directory (TOML / Markdown / BibTeX); no code changes are needed for content updates.

## Development

Requires Node.js 22+.

```bash
npm install
npm run dev     # http://localhost:3000
npm run build   # static export to out/
```

## Deployment

The site is deployed to GitHub Pages via the GitHub Actions workflow in
[`.github/workflows/deploy.yml`](.github/workflows/deploy.yml). In the repository
settings, set **Settings → Pages → Build and deployment → Source** to
**GitHub Actions**.
