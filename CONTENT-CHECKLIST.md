# Content checklist — what to add before/after launch

The site is fully functional as-is, but these additions take it from "strong" to "undeniable."
Placeholders on the site are styled as dashed chips ("＋ Add: …") or dashed boxes ("Add: screenshot…") — search the HTML for `metric-todo`, `img-slot`, and `TODO` to find them all.

## 1. Numbers to collect (highest leverage — do this first)

Approximate-but-honest is fine ("~$15k/mo", "roughly 40%"). Never invent.

**The Rugs Story** (`work/paid-media-rugs-story.html`) — ✅ DONE (added Jul 2026)
- [x] $15K–$40K/mo managed · 2–3x blended ROAS · ~15% acquisition-efficiency gain · US/UK/EU · IG 7K→16K · ELLE Decor

**SixSails** — on homepage experience section (numbers intentionally omitted per Mehar)
- [x] CPA at/below client targets · multi-account portfolio

**Healthy18** (`work/seo-healthy18.html`) — mostly done
- [x] ~2x organic sessions in 15 months
- [ ] Keywords moved to page 1
- [ ] Articles published

**SILKWOX** (`work/silkwox.html`)
- [ ] Total orders or revenue
- [ ] Best ROAS
- [ ] AOV

**ShelfSpace / AI Rank / TrendingBoard** (`work/shelfspace.html`, etc.)
- [ ] Audits sold, revenue, signups, subscribers, brands checked — whatever exists, even small numbers framed as "first N weeks"

**FirstClass Insurance CRM** (`work/firstclass-crm.html`) — this page needs YOUR review most:
- [ ] Which CRM platform you used (page currently says "Add CRM platform")
- [ ] Project dates
- [ ] Replace the generic "What I built" bullets with what you actually implemented
- [ ] Any before/after numbers (leads/month, follow-up rate, time saved)

**How to insert a real number:** replace
`<span class="metric-todo">＋ Add: ROAS achieved</span>` with
`<span class="chip accent">3.2x blended ROAS</span>` (the styled "real" chip).

## 2. Images & video to add

- [ ] **Tableau dashboard screenshot** — export from `finalproject_mehar_luk.twbx`, and ideally publish to **Tableau Public** (free) so recruiters can interact; link it in `work/retail-analytics-dashboard.html`. This is the #1 asset for analytics roles.
- [x] **Tableau Public embed** — the WOW 2023 Week 5 sales-pipeline funnel chart is embedded on the analytics case-study page and linked from the homepage. NOTE: it's described as a "Workout Wednesday community challenge build" — if that viz isn't on your own Tableau Public profile, swap in your own published version.
- [ ] **UGC videos** — record 2–3 of the ad concepts in the Creative section yourself on a phone (even rough). Real video in those slots is a massive differentiator; replace each `.video-slot` div with a `<video>` embed or GIF.
- [x] Ad-account proof screenshots — added Jul 2026 as the "Proof of Work" section (`proof/` folder: 2 Ads Manager tables, lifetime results, Shopify sales, analytics highlights).
- [ ] Screenshots still open: ShelfSpace landing page + sample report, AI Rank results for a known brand, TrendingBoard dashboard, SILKWOX store, Search Console traffic view for Healthy18.
- [ ] A second photo of you (candid/working) for the About section if you want variety — both slots currently reuse `mehar.jpg`.

## 3. Quick wins

- [ ] Update `Mehar_Singh_Resume.pdf` to match the site's positioning (Desktop copy is from May).
- [ ] Add your GitHub link to the contact section if you want to show the product code.
- [ ] Publish the Tableau workbook to Tableau Public and add the link in two places (analytics section + case study).
- [ ] Once ShelfSpace has even 1–2 paying customers, add a testimonial quote to its case study.
- [ ] Consider a custom OG image (1200×630) for link previews; currently uses your headshot.

## 4. Headline alternatives (current: "I turn ad spend, search, and data into measurable growth.")

1. "Marketing that pays for itself."
2. "Performance marketer who ships — ads, analytics, and the products behind them."
3. "Growth isn't a guess. I measure it, build it, and scale it."
4. "From first click to final dashboard, I run growth end to end."

Swap in `index.html` (the `<h1>` in the hero) if one fits you better.

## 5. Deploy

Same as before — push these files to the GitHub repo connected to Vercel:
`index.html`, `styles.css`, `work/` (whole folder), `mehar.jpg`, `Mehar_Singh_Resume.pdf`, `CNAME`.
Note: this local repo has no git remote configured — re-add it (`git remote add origin <repo-url>`) or upload via GitHub's web UI.
