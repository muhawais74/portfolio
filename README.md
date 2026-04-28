# Muhammad Awais — Portfolio

A clean, bold, single-page portfolio site built in pure HTML, CSS & vanilla JS. Designed for quick hosting on GitHub Pages.

## 🚀 Quick deploy to GitHub Pages

You have two options. **Option 1 is the fastest** — your site goes live at `muhawais74.github.io` (no `/something` after).

### Option 1: User Site (recommended) — `muhawais74.github.io`

1. On GitHub, create a new public repository named **exactly**: `muhawais74.github.io`
   _(replace `muhawais74` with your real GitHub username — yours is `muhawais74` so it's already correct)_
2. Upload `index.html`, `styles.css`, and `script.js` to that repo (drag-and-drop on github.com works fine).
3. Go to **Settings → Pages**.
4. Under "Build and deployment", set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`), folder `/ (root)`
5. Save. Wait ~1–2 minutes.
6. Your site is live at: **https://muhawais74.github.io**

### Option 2: Project site — `muhawais74.github.io/portfolio`

1. Create a public repo with any name, e.g. `portfolio`.
2. Upload the three files.
3. Settings → Pages → Source: `main` branch, `/ (root)` folder.
4. Site goes live at: `https://muhawais74.github.io/portfolio/`

## 📝 How to update content

Everything is in `index.html` — search for the section and edit text directly.

- **Hero stats** — change `data-target="60"` etc.
- **Projects** — duplicate any `<a class="project">` block to add a new one.
- **Email** — search for `muhdawais.dev@gmail.com` and replace if it ever changes.

## 🎨 Tweaking the design

Open `styles.css` — all colors are CSS variables at the top:

```css
:root {
  --ink: #0a0a0a;       /* main background */
  --cream: #f5f1e8;     /* main text */
  --lime: #c6ff3a;      /* accent / brand */
  ...
}
```

Change those four values and the whole site re-themes itself.

## 📁 Files

- `index.html` — markup
- `styles.css` — all styles
- `script.js` — counters, scroll reveals, mobile menu, cursor glow

No build step. No npm install. Just three files.
