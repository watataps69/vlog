# Kapuluan — Philippine Travel Blog

A static website built for a website-development activity, based on the
"10 Best Places to Visit in the Philippines" blog content.

## What's inside
- `index.html` — home page
- `blog.html` — blog listing (all destination write-ups)
- `about.html` — about the project
- `contact.html` — contact form (front-end only, no backend wired up)
- `posts/` — 8 individual blog posts (Boracay, El Nido, Coron, Cebu, Bohol,
  Siargao, Banaue, Davao)
- `css/style.css` — all styling, responsive from mobile to desktop
- `js/main.js` — mobile nav toggle + demo contact form handler

## Before you submit
The photos currently use https://picsum.photos placeholder images so the
site works immediately with no setup. Swap them for real, royalty-free
photos of each destination (e.g. from Unsplash or Pexels, crediting the
photographer per that site's license) before turning this in — just replace
the `img src` URLs in each HTML file, or the `img=` values in `build.py` and
re-run the script if you'd rather regenerate everything.

## How to deploy it live (pick one)

### Option A — GitHub Pages (free, no install needed)
1. Create a new GitHub repository and upload every file in this folder,
   keeping the same structure (don't put them in a subfolder).
2. In the repo, go to Settings → Pages.
3. Under "Build and deployment", set Source to "Deploy from a branch",
   choose the `main` branch and `/ (root)`, then Save.
4. GitHub gives you a live URL after a minute or two, usually
   `https://<your-username>.github.io/<repo-name>/`.

### Option B — Netlify Drop (fastest, drag-and-drop)
1. Go to https://app.netlify.com/drop
2. Drag this whole folder onto the page.
3. Netlify gives you a live URL immediately. You can rename it in
   Site settings → Change site name.

### Option C — Vercel
1. Go to https://vercel.com/new and sign in.
2. Import this folder as a new project (or push it to a GitHub repo first
   and import that).
3. Leave the framework preset as "Other" — it's a static site, no build
   command needed. Deploy.

Any of these give you a real, shareable URL to submit alongside your files.
