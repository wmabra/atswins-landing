# ATSwins Landing Page — Project State

> **Repo:** https://github.com/wmabra/atswins-landing · **Branch:** `master` · **Local path:** `~/github/atswins-landing`
> **Fresh-machine resume:** static site, no build step. `git clone` → edit `index.html` → deploy.
> **Last updated:** 2026-10-21 · **Last code change:** 2026-07-08 · **Status:** deployed, static, no build

## What this is

The ATSwins.ai marketing landing page — a **single hand-written `index.html`** (631 lines) with inline CSS/JS. Title: "ATSwins — AI-Driven Sports Intelligence".

## Files

| Path | Purpose |
| --- | --- |
| `index.html` | The whole page (hero, features, pricing, CTA) — inline CSS + JS |
| `training-scripts.md` | 13 training-video scripts (474 lines) — marketing content, not code |
| `robots.txt` / `sitemap.xml` | SEO |
| `vercel.json` | `cleanUrls: true`, `trailingSlash: false` |

## Deploy

Hosted on **Vercel**. `.vercel/` (project link metadata) is gitignored — on a new
machine run `vercel link` once, then `vercel --prod`.

Deployed from a single commit (`b01d927`) — there is no CI; pushes do not auto-deploy
unless the Vercel Git integration was connected on the dashboard.

## Notes

- No `README.md` upstream — this file is the entry point.
- Everything is inline by design; do not introduce a bundler without a reason.
- `training-scripts.md` is the source for the ATSwins training/onboarding videos.
