# scraping-services — landing page

A single-page site advertising freelance web-scraping services. Static HTML/CSS,
no build step, no dependencies. Designed to be hosted free on **GitHub Pages**.

## Live site
Once GitHub Pages is enabled: `https://salcar420.github.io/scraping-services/`

## Before sharing it — edit two things in `index.html`
1. `YOUR_EMAIL_HERE` → your real email (in the Contact button `mailto:`).
2. `UPWORK_PROFILE_URL` → your Upwork profile link.

(Optional) tweak the brand name `scrappy.dev`, colors (`:root` variables) or copy.

## Enable GitHub Pages
Repo → Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `/ (root)` → Save.
Or via CLI: `gh api -X POST repos/salcar420/scraping-services/pages -f "source[branch]=main" -f "source[path]=/"`

## Why this matters
Most freelancers only have an Upwork profile. A clean services page makes you look like
a real business: you can link it in proposals, your GitHub bio, and social profiles —
it raises trust and lets you charge more.
