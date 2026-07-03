# Patricia Woods Bookkeeping — Website

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

**Option A — Netlify Drop (easiest):**
1. Go to https://app.netlify.com/drop
2. Drag the folder containing `index.html` onto the page.
3. That's it — you get a live link immediately. Create a free account to keep
   it and to set a custom name (or connect a domain you buy later).

**Option B — GitHub Pages (already half done, since this repo exists):**
1. On this repository's GitHub page, go to **Settings → Pages**.
2. Under "Build and deployment", choose **Deploy from a branch**, pick your
   main branch and the `/ (root)` folder, and save.
3. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

A custom domain (e.g. `patriciawoodsbookkeeping.com`) can be pointed at
either option later — both have simple guides for it.

## Placeholders still waiting for your real details

Search `index.html` for `[EDIT:` to find them all. The full list:

| Where | What's needed |
|---|---|
| About — story paragraph | A light personal line (`[EDIT: a gentle joke — e.g. "two tax seasons ago"]`) |
| About — facts list | Your years of experience |
| About — facts list | Your town/area and whether you serve clients remotely |
| About — facts list | A credential or specialty (e.g. QuickBooks certification) |
| Testimonials (×3) | Real client quotes, names, and business types — the three quotes there now are **clearly marked samples** |
| FAQ — "meet in person" | Your local meeting preference |

Everything else is finished copy you can keep, trim, or rewrite in your own
voice.
