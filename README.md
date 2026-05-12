# Phat Panda Group — Retail Dashboards

A simple front page listing every store and its monthly + weekly performance dashboard. Built as a static site, ready to drop on Vercel.

## What's in here

- `index.html` — the front page (lists 6 stores + portfolio rollups, with reports per store)
- `reports/` — self-hosted monthly dashboards
  - EMBR Lake Elsinore, La Mesa, Northampton, Springfield, and Fyre Ants
- Weekly dashboards, Higher Level Greenfield's monthly, and the All-Stores rollups link to Google Drive so they stay current automatically
- `vercel.json` — clean URLs config
- `.gitignore` — standard ignores

## Deploy to Vercel (one command)

From this folder on your machine:

```bash
npx vercel --prod
```

That will:
1. Prompt you to log in (browser) the first time
2. Ask if this is a new project — say yes, accept defaults
3. Print a `https://*.vercel.app` URL — that's your live site

To redeploy later, just run `vercel --prod` again from the same folder.

## Push to GitHub

The repo is already initialized with two commits. From this folder:

```bash
# Create a new empty repo on github.com first, then:
git remote add origin git@github.com:<your-username>/phat-panda-dashboards.git
git push -u origin main
```

If you want Vercel to auto-deploy on every `git push`, link the GitHub 