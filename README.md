# meharsingh.com — portfolio site

Recruiter-focused marketing portfolio. Static, no build step.

## Files

- `index.html` — homepage (hero, proof strip, case studies, UGC/creative, websites, analytics, about, skills, contact)
- `work/*.html` — 8 case-study pages
- `styles.css` — shared design system (Space Grotesk + Inter, mobile-first)
- `mehar.jpg` — profile photo
- `Mehar_Singh_Resume.pdf` — resume download
- `CNAME` — custom domain (meharsingh.com)
- `CONTENT-CHECKLIST.md` — metrics, images, and video still to add (read this!)

## Deploy

Push everything (including the `work/` folder) to the GitHub repository connected to Vercel.
This local repo currently has **no git remote** — re-add it first:
`git remote add origin <your-repo-url>` then `git push`.

## Editing

- Placeholder metrics look like dashed chips: `<span class="metric-todo">＋ Add: …</span>`.
  Replace with `<span class="chip accent">real number</span>` when you have the figure.
- Placeholder image boxes use `class="img-slot"` — replace the div with an `<img>`.
