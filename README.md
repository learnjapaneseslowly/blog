# Blog — deploy notes

## What this is
A static blog, ready to deploy for free. No server, no database, no monthly fee.

## Stack (per the roadmap)
- Static HTML (SSG-equivalent for v1; move to Astro/Hugo later without changing URLs)
- Deploy to Cloudflare Pages or GitHub Pages
- Free subdomain: `*.pages.dev` or `*.github.io`

## Deploy — Cloudflare Pages
1. Create a free Cloudflare account.
2. Push this `blog/` folder to GitHub.
3. In Cloudflare Pages, connect the repo, set the build output to the repo root, no build command.
4. Publish. Your site is live on `*.pages.dev`.

## Deploy — GitHub Pages (alternative)
1. Push `blog/` to a GitHub repo.
2. Settings → Pages → deploy from the main branch, root folder.
3. Publish. Your site is live on `*.github.io`.

## Next steps (not yet done — needs accounts)
- GitHub account connection / repo creation
- Cloudflare account connection
- Google Search Console registration + sitemap submission
- Canonical URLs for Medium / Dev.to / Hashnode reposts

## Posts
- `posts/learn-japanese-15-minutes-a-day.html`
- `posts/10-japanese-words-beginners.html`
- `posts/notion-japanese-learning.html`

## Source of truth
Notion brain hub: https://app.notion.com/p/41d263e6dfc2810c990df5cd330f2ef1?pvs=204
Template v1: https://app.notion.com/p/41d263e6dfc281e281beda3725118f8a?pvs=204
