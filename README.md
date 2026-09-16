# FreyTech website concept — private client review preview

This repository publishes a **review preview** of the proposed Frey Technologies website to GitHub Pages. It is not the live freytech.org site, it is marked `noindex`, and its forms are intentionally not connected (nothing is transmitted).

- Preview URL: https://alexanderbill995-ship-it.github.io/freytech-preview/
- Stack: Next.js static export, TypeScript, CSS Modules. Build: `npm ci && npm run build` (output in `out/`).
- Deployment: `.github/workflows/pages.yml` (official GitHub Pages Actions) sets `NEXT_PUBLIC_BASE_PATH` to the repository name and `NEXT_PUBLIC_PREVIEW=true`.
- Content is data-driven from `src/content/`; see `docs/OWNER-HANDOFF.md`, `docs/ROUTE-MAP.md`, `docs/FORM-DELIVERY-DECISION.md`.

Items shown with an "Under review" marker are pending confirmation with FreyTech before publication.
