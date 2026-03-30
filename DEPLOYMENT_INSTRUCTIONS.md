# D2 Referral Hub — Vercel Deployment (Manual)

**Status:** Git repo initialized locally. Ready for Vercel deployment.

## Option 1: Deploy via GitHub + Vercel (Recommended - 5 min)

### Step 1: Create GitHub repo
1. Go to https://github.com/new
2. Create repo: `d2-referral-hub` (or similar)
3. Copy the repo URL (HTTPS)

### Step 2: Push to GitHub
```bash
cd /Users/OpenClaw/.openclaw/workspace/d2_passive_income
git remote add origin https://github.com/YOUR_USERNAME/d2-referral-hub.git
git branch -M main
git push -u origin main
```

### Step 3: Deploy to Vercel
1. Go to https://vercel.com/new
2. Import from GitHub → select `d2-referral-hub`
3. Click "Deploy"
4. Wait ~30 seconds → Live URL (e.g., `d2-referral-hub.vercel.app`)

**That's it.** Your site is live.

---

## Option 2: Deploy via Vercel CLI (if installed)

```bash
cd /Users/OpenClaw/.openclaw/workspace/d2_passive_income
vercel deploy
```

Then follow Vercel's CLI prompts.

---

## Option 3: Manual HTML Upload via Vercel Web

1. Go to https://vercel.com/new
2. Select "HTML / CSS / JS"
3. Upload the entire `d2_passive_income` folder
4. Deploy

---

## What Gets Deployed

- `index.html` — Main hub (links to all 5 landing pages)
- `landing_pages/` — 5 SEO-optimized referral pages
  - `billcom-ap.html`
  - `billcom-spend.html`
  - `servicetitan.html`
  - `amex-platinum.html`
  - `tesla.html`
- `tracking/referral-tracking.md` — Dashboard template
- `CONTENT_STRATEGY.md` — Blog roadmap

---

## After Deployment

1. Test all landing pages in browser
2. Set up Google Search Console (add domain, submit sitemap)
3. Create first blog post (based on CONTENT_STRATEGY.md keywords)
4. Monitor organic traffic in GSC

---

## Live URL Once Deployed

Will be provided by Vercel (format: `[project-name].vercel.app`)

---

**Questions?** See `START_HERE.md` for quick reference.
