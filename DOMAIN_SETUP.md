# Put TheLight at thelight.2amcases.online (free; Chris's choice 2026-11-01)

2amcases.online is on GitHub Pages with DNS at Namecheap, so a subdomain needs two small things. The `CNAME` file in this repo is already added.

## 1. Namecheap (an adult has the login, or Chris with mom there)
Domain List > 2amcases.online > Advanced DNS > Add New Record:
- Type: **CNAME Record**
- Host: **thelight**
- Value: **chriscancod.github.io**
- TTL: Automatic
This does not touch the main 2AM site (its own records stay as they are).

## 2. GitHub (this turns the page public, so Chris does it himself)
Repo `chriscancod/thelight` > Settings > Pages:
- Source: Deploy from a branch, **main**, folder **/ (root)**.
- Custom domain: **thelight.2amcases.online** > Save.
- After the DNS check goes green (can take up to an hour), tick **Enforce HTTPS**.
**Catch:** GitHub Pages from a PRIVATE repo needs a paid GitHub plan. On the free plan the repo has to be made public, which lets anyone read `index.html` (nothing secret is in it; it only has public image links). Chris and mom decide which.

## What visitors will see
The page says "Preview only · not live · no checkout · prices and pieces are proposals" and tags every piece "Proposed". It shows 2AM-marked sample images until TheLight prints exist (see LAUNCH_BLOCKERS.md). That wording is honest; keep it until there is a real checkout.

## Check it worked
`dig +short thelight.2amcases.online` should answer `chriscancod.github.io.` and then the page loads over https.
