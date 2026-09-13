# Deploying the ddeploy site

Static files, no build step, no dependencies. Deploy anywhere.

## Fastest: Cloudflare Pages (free)
1. Push the `site/` folder to a GitHub repo (or drag-drop the folder at pages.cloudflare.com).
2. Framework preset: None. Build command: none. Output dir: /
3. Custom domain is ddeploy.com (DNS in the personal Cloudflare account, nameservers at GoDaddy).

## Or GitHub Pages
Repo → Settings → Pages → deploy from branch, folder = site/.

## Before going live
- Domain is ddeploy.com everywhere; the live site is the GitHub Pages mirror `anandat/ddeploy-site`, pushed by `release-adhoc.sh`.
- Replace downloads/ddeploy.dmg with the notarized build from release.sh, then delete
  the "Beta build" line in the index hero and the install FAQ caveat.
- Point the Pro buttons at the Dodo checkout URL once the store is live.
