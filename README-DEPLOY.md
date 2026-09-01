# Deploying the ddeploy site

Static files, no build step, no dependencies. Deploy anywhere.

## Fastest: Cloudflare Pages (free)
1. Push the `site/` folder to a GitHub repo (or drag-drop the folder at pages.cloudflare.com).
2. Framework preset: None. Build command: none. Output dir: /
3. Add the custom domain (e.g. ddeploy.app) — Cloudflare walks you through the CNAME.

## Or GitHub Pages
Repo → Settings → Pages → deploy from branch, folder = site/.

## Before going live
- Search-replace `ddeploy.app` with the real domain (index, faq, blog pages, robots.txt, sitemap.xml).
- Replace downloads/ddeploy.dmg with the notarized build from release.sh, then delete
  the "Beta build" line in the index hero and the install FAQ caveat.
- Point the Pro buttons at the Dodo checkout URL once the store is live.
