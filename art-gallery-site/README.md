# Your Art Gallery Website

A clean white gallery. Visitors browse your art and mockups; buying happens on Gumroad.

## What's in this folder
- `index.html` — the whole website (you never need to touch it)
- `data/artworks.json` — your list of artworks (edited for you by the upload dashboard)
- `data/site.json` — your name, tagline, about text, and social links
- `images/` — where your artwork and mockup images are stored
- `.pages.yml` — settings for the upload dashboard
- `.nojekyll` — tells GitHub to serve the site as-is

## One-time setup (about 20 minutes)
- [ ] 1. Create a free account at github.com
- [ ] 2. Create a new **public** repository named exactly `YOURUSERNAME.github.io`
- [ ] 3. Click "uploading an existing file" and drag in EVERYTHING inside this folder
      (including `.pages.yml` and `.nojekyll` — on a Mac press Cmd+Shift+. to see hidden files). Click "Commit changes".
- [ ] 4. In the repository: Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save
- [ ] 5. Wait 1–2 minutes, then visit `https://YOURUSERNAME.github.io` — your site is live
- [ ] 6. Go to app.pagescms.org → Sign in with GitHub → allow access to your repository → open it

## Adding a new artwork
1. Open app.pagescms.org → your site → **Artworks**
2. Click **Add an entry**, fill in title and category
3. Upload the main image, then upload each mockup
4. Paste the Gumroad link for that piece → **Save**
5. The site updates by itself in about a minute

## Before you go live
- Delete the 8 sample pieces in Artworks (and their files under Media)
- Fill in **Site settings**: your name, tagline, about, and links

## Image tips
- Save web-sized JPGs: about 2000px on the long side, under 1 MB each
- Keep full-resolution files for Gumroad only — never upload them here
- Add your watermark before uploading if you like
