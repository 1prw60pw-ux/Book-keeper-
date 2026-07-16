# Integrity Bookkeeping Service — Website

Business: **Integrity Bookkeeping Service** (Patricia Woods) ·
Domain: **woodsintegrityservice.com**

The entire website is **one file: `index.html`**. No installs, no builds, no
subscriptions. Double-click it and it opens in your browser, working exactly
as it will online.

---

## How to edit the text

1. Open `index.html` in any plain-text editor (Notepad on Windows, TextEdit
   on Mac — or, nicer, the free [VS Code](https://code.visualstudio.com)).
2. Press `Ctrl+F` (Windows) / `Cmd+F` (Mac) and search for the section you
   want. There's a map in a comment at the very top of the file:
   - `HERO SECTION` — the big headline at the top
   - `ABOUT SECTION` — your story
   - `SERVICES SECTION` — the service cards
   - `WHY SECTION` — the four promises
   - `PROCESS SECTION` — the 3 steps
   - `TESTIMONIALS SECTION` — client quotes
   - `FAQ SECTION` — questions & answers
   - `CONTACT SECTION` — the form
3. Change the words between the tags (e.g. between `<p>` and `</p>`),
   save the file, and refresh your browser to see it.

**To change the email address:** search for `1prw60.pw@gmail.com` and replace
every occurrence (it appears a few times, including once in the JavaScript
near the bottom as `BUSINESS_EMAIL`).

**To change the colors:** search for `COLOR PALETTE` — the six color codes at
the top of the styles control the whole site.

## How to add your photo and logo

- **Headshot:** search for `HEADSHOT PLACEHOLDER`. The comment there shows the
  exact line to paste in. Put your photo file (e.g. `patricia.jpg`) in the
  same folder as `index.html`.
- **Logo:** search for `LOGO PLACEHOLDER` in the navigation. Same idea — the
  comment shows what to replace. (The gold "PW" monogram works nicely until
  you have one.)

## How to put it online — free, in about 2 minutes

**Option A — Vercel (recommended; this repo is ready for it):**
1. Go to https://vercel.com and sign up free with your GitHub account.
2. Click **Add New → Project** and pick this repository.
3. Change nothing — no framework, no build command — and click **Deploy**.
4. Your site is live at `https://<project-name>.vercel.app` in about
   30 seconds, and it automatically redeploys every time the site files
   change on GitHub.
5. **Connect the real domain:** go to **Project → Settings → Domains**,
   type `woodsintegrityservice.com`, and follow the two DNS steps Vercel
   shows you (you set those at the company where the domain was bought).
   Vercel handles the HTTPS certificate automatically, and it's smart to
   let it redirect `www.woodsintegrityservice.com` to the main domain
   (it offers this during setup).

   (The `vercel.json` file in this folder is already set up — it adds
   security headers and tidy URLs. You never need to touch it.)

**Option B — Netlify Drop (no account needed to try):**
1. Go to https://app.netlify.com/drop
2. Drag the folder containing `index.html` onto the page.
3. That's it — you get a live link immediately. Create a free account to keep
   it and to set a custom name (or connect a domain you buy later).

**Option C — GitHub Pages (already half done, since this repo exists):**
1. On this repository's GitHub page, go to **Settings → Pages**.
2. Under "Build and deployment", choose **Deploy from a branch**, pick your
   main branch and the `/ (root)` folder, and save.
3. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

`woodsintegrityservice.com` can be pointed at options B and C too, but
Vercel's domain setup (option A, step 5) is the smoothest.

## SEO — what's built in, and the 30 minutes that matter most

**Already built into the site** (nothing to do):
- Search-optimized page title and description
- Structured data (schema.org) telling Google this is an accounting/bookkeeping
  service, who runs it, all seven services, and the full FAQ — the FAQ is
  eligible to appear directly in Google results
- A social-share card (`og-image.png`) so links look professional when texted
  or posted on Facebook/LinkedIn
- `sitemap.xml` and `robots.txt` for search-engine crawlers
- Fast, mobile-friendly, accessible single page — all things Google rewards

**The highest-impact things only Patricia can do** (each is free):
1. **Google Business Profile** — the single biggest lever for a local service
   business. Create one at https://business.google.com with the exact name
   "Integrity Bookkeeping Service", the website link, and the service list.
   This is what puts the business on Google Maps and in the local results box.
2. **Google Search Console** — at https://search.google.com/search-console,
   add the domain, verify it (Vercel makes this a one-click DNS record), and
   submit `https://woodsintegrityservice.com/sitemap.xml`. This gets the site
   indexed fast and shows what people searched to find it.
3. **Reviews** — after each happy client, ask for a Google review on the
   Business Profile. Five genuine reviews outrank a thousand keywords.
4. **Real details on the page** — filling in the `[EDIT:]` placeholders
   (years of experience, book titles, real testimonials) directly improves
   how trustworthy the page looks to both people and Google.
5. **A few good links** — a listing in the local chamber of commerce,
   QuickBooks ProAdvisor directory (if certified), and Patricia's author
   pages linking to the site all build authority.

## Placeholders still waiting for your real details

Search `index.html` for `[EDIT:` to find them all. The full list:

| Where | What's needed |
|---|---|
| About — "Off the clock" cards | Your book title(s) under "Published author" |
| About — facts list | Your years of experience |
| About — facts list | A credential or specialty (e.g. QuickBooks certification) |
| Testimonials (×3) | Real client quotes, names, and business types — the three quotes there now are **clearly marked samples** |
| FAQ — "meet in person" | Your local meeting preference |

Everything else is finished copy you can keep, trim, or rewrite in your own
voice.
